# CodeRev

## Data Generation
```
python -m generate_instruction generate_instruction_following_data \
  --output_dir="./" \
  --num_instructions_to_generate=100 \
  --model_name="gpt-3.5-turbo-16k" \
  --similarity_threshold=1
```

## Finetuning
Coming soon...