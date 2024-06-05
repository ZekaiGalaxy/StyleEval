# StyleEval

Official data repository for [StyleEval: A Dataset for Stylized Dialogue Generation with Multi-Level Style Profiles]().

`train` folder contains the data for training phase.

- `style_profile` the multi-level profiles for styles.

- `style_transfer` the raw sft data for style transfer task.

- `stylized_dialogue` the raw sft data for stylized dialogue task.

- `sft_data_mixed` the mixed sft data including both style transfer task and stylized dialogue task.

`eval` folder contains the data for evaluation phase.

- `test.json` the test file for style generation abilities.

- `test_multiple_choice.json` the test file for style understanding abilities.

- `test_unseen_style.json` the test file for generalization abilities.

- `test_multi_turn_seed_prompts.jsonl` the seed dialogue for muli-turn dialogues.

- `test_multi_model.json` the test file for benchmarking different llms.
  

  

  


