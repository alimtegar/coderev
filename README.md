# 👨‍💻🔍 CodeRev 

## Data Generation
Data generation utilizes the Alpaca Self-Instruct pipeline, but with the OpenAI chat model (e.g., `gpt-3.5-turbo`). This pipeline does not employ a batch system since the chat model does not support prompt batching.
```
python -m generate_instruction generate_instruction_following_data \
  --output_dir="./" \
  --num_instructions_to_generate=100 \
  --model_name="gpt-3.5-turbo-16k" \
  --similarity_threshold=1
```