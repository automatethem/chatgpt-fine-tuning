# chatgpt-fine-tuning

## 포인트 충전

https://platform.openai.com/settings/organization/billing/overview

![](attach_files/b.png?raw=true)

## 파인 튜닝

### davinci-002

https://platform.openai.com/finetune

https://github.com/automatethem/datasets/blob/main/completion/factual-sarcastic/train.jsonl
```
{"prompt": "세상에서 가장 작은 나라는 어디인가요?", "completion": "바티칸 시국이죠. 거기가 사실 나라라고 할 수 있을 정도로 크다고 생각하시나요?"}
```

![](attach_files/ft-1-0.png?raw=true)

![](attach_files/ft-1-1.png?raw=true)

![](attach_files/ft-1-2.png?raw=true)

![](attach_files/ft-1-3.png?raw=true)

![](attach_files/ft-1-4.png?raw=true)

![](attach_files/ft-1-5.png?raw=true)

```
ft:davinci-002:cranberry:factual-sarcastic:9FLfFO8R
```

예측  
https://platform.openai.com/playground/complete

![](attach_files/ft-1-6.png?raw=true)

### babbage-002, gpt-3.5-turbo-1106

https://platform.openai.com/finetune

https://github.com/automatethem/datasets/blob/main/chat/factual-sarcastic/train.jsonl
```
{"messages": [{"role": "system", "content": "당신은 사실적이며 냉소작인 챗봇 입니다."}, {"role": "user", "content": "세상에서 가장 작은 나라는 어디인가요?"}, {"role": "assistant", "content": "바티칸 시국이죠. 거기가 사실 나라라고 할 수 있을 정도로 크다고 생각하시나요?"}]}
```

![](attach_files/ft-2-0.png?raw=true)

![](attach_files/ft-2-1.png?raw=true)

![](attach_files/ft-2-2.png?raw=true)

![](attach_files/ft-2-3.png?raw=true)

![](attach_files/ft-2-4.png?raw=true)

![](attach_files/ft-2-5.png?raw=true)

```
ft:gpt-3.5-turbo-1106:cranberry:factual-sarcastic:9FLkDqVd
```

예측  
https://platform.openai.com/playground/chat

![](attach_files/ft-2-6.png?raw=true)
