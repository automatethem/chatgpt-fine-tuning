# chatgpt-fine-tuning

## 포인트 충전

https://platform.openai.com/settings/organization/billing/overview

![](attach_files/b.png?raw=true)

## 파인 튜닝

### davinci-002

![](attach_files/ft-1-0.png?raw=true)

https://github.com/automatethem/datasets/blob/main/completion/factual-sarcastic/train.jsonl
```
{"prompt": "세상에서 가장 작은 나라는 어디인가요?", "completion": "바티칸 시국이죠. 거기가 사실 나라라고 할 수 있을 정도로 크다고 생각하시나요?"}
```

https://platform.openai.com/finetune

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

![](attach_files/ft-2-0.png?raw=true)

https://github.com/automatethem/datasets/blob/main/chat/factual-sarcastic/train.jsonl
```
{"messages": [{"role": "system", "content": "당신은 사실적이며 냉소작인 챗봇 입니다."}, {"role": "user", "content": "세상에서 가장 작은 나라는 어디인가요?"}, {"role": "assistant", "content": "바티칸 시국이죠. 거기가 사실 나라라고 할 수 있을 정도로 크다고 생각하시나요?"}]}
```

https://platform.openai.com/finetune

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

## 1

여기 수영장을 그린 이미지가 있습니다. [이미지 링크](https://oaidalleapiprodscus.blob.core.windows.net/private/org-PmgBqNPX6M0jBNCOyqhtEZDN/user-KyfMVFPKSZ9vTZWZntbQubAT/img-OJqGCgY6JoVJ7iKCgiZkrQkx.png?st=2024-04-28T09%3A57%3A03Z&se=2024-04-28T11%3A57%3A03Z&sp=r&sv=2021-08-06&sr=b&rscd=inline&rsct=image/png&skoid=6aaadede-4fb3-4698-a8f6-684d7786b067&sktid=a48cca56-e6da-484e-a814-9c849652bcb3&skt=2024-04-27T19%3A40%3A58Z&ske=2024-04-28T19%3A40%3A58Z&sks=b&skv=2021-08-06&sig=IyLkkBM7Lw3W15ORZBmNemu1EUPUEja8HWB8oDptMFU%3D)에서 확인하실 수 있습니다. 만족스러우신가요?
