# Llama2-chat-interface

![Screenshot of chat interface](./assets/llama2-chat-demo.png)


## Start Interface

```
torchrun --nproc_per_node 1 chat.py --ckpt_dir llama-2-7b-chat/ --tokenizer_path tokenizer.model --max_seq_len 512 --max_batch_size 4
```