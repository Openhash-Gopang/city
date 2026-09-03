# K-City — 시민 복지 총합 최적 도시 설계

혼디(Hondi) K-서비스 중 하나. 도시(읍·면·동 단위 포함) 전체의 시민
복지 총합(주거·의료·교육·금융·교통·통신·레저 등)이 최상이 되는 각
시설의 물리적 조합(입지·규모·용량 배분)을 설계한다.

- 상태: 초안 (v0.1) — 아직 sp-catalog.json에 등록되지 않았고,
  worker.js 라우팅에도 연결되지 않았다.
- 설계 문서: [`SP-27_kcity_v0_1.txt`](./SP-27_kcity_v0_1.txt)
- 관련 저장소: [hondi](https://github.com/Openhash-Gopang/hondi)(메인)
- K-City의 산출물은 **자문 설계안**이며, 실제 인허가·행정처분은 항상
  해당 지자체·국가기관의 법정 권한이다(K-Law의 면책 구조와 동일한
  원칙).

## 다음 단계

1. `SP-27_kcity_v0_1.txt`를 hondi 메인 저장소의 `prompts/`에 반영하고
   sp-catalog.json에 등록
2. §WELFARE-FUNCTION 가중치·계량 모델의 실증 근거 확보
3. K-Democracy(시민 심의)·K-JIT(장기 조달 예측) 연동 지점 실사
4. worker.js 라우팅 연결 및 desktop.html#k-services 탭 추가
