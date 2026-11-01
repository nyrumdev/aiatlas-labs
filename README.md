# AI 아틀라스 실습 키트 · AI Atlas lab kits

AI 아틀라스 앱의 실습에서 PC 로 그대로 쓰는 파일 묶음입니다. 키트는 누구나 무료로 받을 수 있습니다. 절차 설명은 앱의 실습 화면에 있고, 앱에서 실습은 앱 안 구매 '실습 패키지'로 열립니다.
Files you use on a PC for the labs in the AI Atlas app. The kits are free for anyone. The step-by-step instructions are in the app, where labs are unlocked by the in-app Practice Pack.

**PC 에서 이 페이지 하나만 즐겨찾기해 두면 됩니다.** 앱 실습 화면의 제목과 같은 줄에서 파일 이름을 누르고, 열린 화면의 내려받기 단추로 받습니다.
Bookmark this one page on your PC. Find the row with the same title as the lab in the app, click the file name, then use the download button.

받은 파일이 바뀌지 않았는지는 SHA-256 으로 견줍니다(PowerShell: `Get-FileHash <파일>`). 앱 실습 화면에도 같은 값이 있습니다.

| 레벨 | 실습 | 파일 | 크기 | SHA-256 |
|---|---|---|---:|---|
| L0 | 같은 문장의 토큰 수 세어 보기 — 한국어·영어, 토크나이저 두 개<br>Counting the tokens in the same sentence — Korean and English, two tokenizers | [aiatlas-lab-token_counter-303f7f4e.zip](kits/aiatlas-lab-token_counter-303f7f4e.zip) | 9KB | `303f7f4e5cfaa2bce582cec007d25bc6d56c0a27a558233ad220cd1e4353a387` |
| L0 | 코드 없이 분류기 학습시키고 일부러 망가뜨리기<br>Train a classifier without code, then break it on purpose | [aiatlas-lab-no_code_classifier-735e6a08.zip](kits/aiatlas-lab-no_code_classifier-735e6a08.zip) | 9KB | `735e6a08a87ad653b312cd75802794b2d3492b88d07cd9bc210b4fd785c1c173` |
| L1 | 스프레드시트로 경사하강법 한 걸음씩 — 코드 없이 직선 하나 맞추기<br>Gradient descent step by step in a spreadsheet — fitting one line without code | [aiatlas-lab-gd_spreadsheet-acb2365d.zip](kits/aiatlas-lab-gd_spreadsheet-acb2365d.zip) | 8KB | `acb2365dcb8d2148a9b0ff2e6f2f098341789948e52c017f063f9bd074bac4c5` |
| L2 | Gemma 4를 내 PC에서 돌리기<br>Running Gemma 4 on My PC | [aiatlas-lab-gemma_local_run-330cc61b.zip](kits/aiatlas-lab-gemma_local_run-330cc61b.zip) | 9KB | `330cc61b35bcee02f1b00bc6ab6ed9d5c56f9466a273753ae96a60a9ff2f05df` |
| L2 | 글자 단위 언어 모델 — 세어서 만든 bigram → 신경망 bigram → 작은 MLP(CPU)<br>Character-level language model — counted bigram → neural bigram → small MLP (CPU) | [aiatlas-lab-char_lm_scratch-5cc2b1b5.zip](kits/aiatlas-lab-char_lm_scratch-5cc2b1b5.zip) | 43KB | `5cc2b1b5ce26dea56dd4ab3814803bc0c1fe3451ece947cc1dfa572bd624a32d` |
| L2 | 기울기를 손으로 — 순수 파이썬 경사하강·기울기 검사에서 작은 자동미분 엔진(micrograd)까지<br>Gradients by hand — from pure-Python gradient descent and gradient checking to a small autodiff engine (micrograd) | [aiatlas-lab-gradients_by_hand-4896bc86.zip](kits/aiatlas-lab-gradients_by_hand-4896bc86.zip) | 33KB | `4896bc8634de6d8e66f19391a0cb4439886ad9acfaed4bc02d653dc569750e9e` |
| L2 | 로컬 QA 앱 만들기<br>Building a Local QA App | [aiatlas-lab-local_qa_app-0bdf9243.zip](kits/aiatlas-lab-local_qa_app-0bdf9243.zip) | 14KB | `0bdf92437df7c14d7b53c80e7c50a18d34896d06434ba21c2d8042f88844a538` |
| L2 | 표데이터 첫 모델을 끝까지 — 기준선·파이프라인·교차검증·잠근 테스트·집단별 오류<br>Your first tabular model, start to finish — baseline · pipeline · cross-validation · locked test · errors by group | [aiatlas-lab-first_model_sklearn-879b4440.zip](kits/aiatlas-lab-first_model_sklearn-879b4440.zip) | 30KB | `879b444075ca52f6709e7d7fce9bf6afd0626e39b393d42ce94bc456ce004ef1` |
| L2 | 한국어 BPE 토크나이저를 직접 짜고 Gemma 4 토크나이저와 비교하기<br>Write a Korean BPE tokenizer yourself and compare it with the Gemma 4 tokenizer | [aiatlas-lab-tokenizer_build-d55e206d.zip](kits/aiatlas-lab-tokenizer_build-d55e206d.zip) | 37KB | `d55e206d6a13451c5812f54de467d2e4e67268b1c52fb83d13763c3e6427c2c6` |
| L3 | 내 RAG·에이전트를 프롬프트 인젝션으로 공격하고 방어 전후 재기<br>Attack your RAG·agent with prompt injection and measure before and after defenses | [aiatlas-lab-injection_redteam-4b5d7481.zip](kits/aiatlas-lab-injection_redteam-4b5d7481.zip) | 40KB | `4b5d748186795fe6292f1c95fb55297c30b6c85fc72ade490ea7efe7c5f8d444` |
| L3 | 내 평가 하네스 만들기(Inspect + lm-eval, 로컬 모델)<br>Build my own evaluation harness (Inspect + lm-eval, local model) | [aiatlas-lab-eval_harness-01929107.zip](kits/aiatlas-lab-eval_harness-01929107.zip) | 41KB | `019291079e5a1bac4c2191490b31f956a885feb8c4f40005851305d29ce5b90b` |
| L3 | 단일 호출 vs 워크플로 vs 에이전트 — 같은 시나리오 셋으로 견주기(에이전트 레슨 4편 직접 해 보기 통합)<br>Single call vs workflow vs agent — comparing them on the same scenario set (combining the 'Try it yourself' parts of the 4 agent lessons) | [aiatlas-lab-tool_agent-485a88b3.zip](kits/aiatlas-lab-tool_agent-485a88b3.zip) | 56KB | `485a88b32caec477c7408f1a16d03ab0289eb4ad7e72571c928a403cb98c054d` |
| L3 | 선호 쌍으로 작은 모델 DPO 한 번 돌리기 — 마진 곡선 · 답 길이 · 회귀<br>Run DPO once on a small model with preference pairs — margin curve · answer length · regressions | [aiatlas-lab-dpo_mini-62b712fb.zip](kits/aiatlas-lab-dpo_mini-62b712fb.zip) | 44KB | `62b712fb97ecb66c946a8d3089b2dc9d8ca41421354662f694e8aafca268e273` |
| L3 | 파인튜닝 1회 + 평가 리포트<br>One Fine-Tuning Run + Evaluation Report | [aiatlas-lab-finetune_report-b34f2d4f.zip](kits/aiatlas-lab-finetune_report-b34f2d4f.zip) | 30KB | `b34f2d4f0686b40e353a529e6a8550e24d43e61ff58453c8585bb9d12c61163a` |
| L4 | 추론 최적화 실험 + 벤치 리포트<br>Inference Optimization Experiment + Benchmark Report | [aiatlas-lab-inference_opt_report-88f025a4.zip](kits/aiatlas-lab-inference_opt_report-88f025a4.zip) | 13KB | `88f025a43806564f116eccdc9c860f3b3f9f231ac8a5cc07ae27e56b079eddc9` |
| L5 | 논문 3편 요약 + 견해 1편<br>Summaries of 3 papers + 1 position paper | [aiatlas-lab-paper_review-0e463de8.zip](kits/aiatlas-lab-paper_review-0e463de8.zip) | 11KB | `0e463de88dad20943db98a9226d17bb43b22d5327a2355b3a2908aeadada5e46` |
| L5 | 소형 모델 GRPO 강화학습 + Pass@k/Maj@k 로 새 능력인지 가리기<br>GRPO reinforcement learning on a small model + using Pass@k/Maj@k to tell whether it is a new ability | [aiatlas-lab-grpo_reasoning-4dcbc97a.zip](kits/aiatlas-lab-grpo_reasoning-4dcbc97a.zip) | 46KB | `4dcbc97a80f9819e56d762274a493f76e6d827d2953dd7c4541795d7cd11b5df` |

코드는 MIT 라이선스(각 키트의 LICENSE)입니다. 모델 가중치·데이터셋은 들어 있지 않으며, 절차대로 원래 배포처에서 받습니다.
