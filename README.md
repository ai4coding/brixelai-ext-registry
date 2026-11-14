# 브릭셀AI 외부(서드파티) 하드웨어 확장 등록부

브릭셀AI 편집기의 확장 센터 **19. 서드파티 하드웨어** 창이 이 저장소의 `registry.json` 을 읽는다
(GitHub Pages: `https://ai4coding.github.io/brixelai-ext-registry/registry.json`).

- **운영자만 고친다.** 업체는 자기 저장소 주소와 커밋을 알려 등록을 요청하고, 운영자가 검토·승인한다.
- 승인 = 그 업체 저장소의 **커밋 하나**에 고정(`main` = jsDelivr `@<커밋>` 주소). 업체가 저장소를 고쳐도 다시 승인하기 전에는 학생 화면이 바뀌지 않는다.
- `vendors` = 운영자가 정한 **업체 코드**(이름표)와 그 업체의 GitHub 계정. 확장 id 는 `ex` + 업체 코드 + 이름이어야 한다.
- 외부 확장은 각 업체가 만들고 관리하며, 동작·안전·지원은 그 업체 책임이다.

이 파일은 손으로 고치지 않는다 — 브릭셀AI 개발 저장소의 `dev-tools/thirdparty-hw/approve.js`(`--add-vendor` · `--approve`)가 쓴다.
