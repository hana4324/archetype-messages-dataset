---
license: mit
---
# Archetype Messages Dataset

This dataset contains 500 examples of personalized messages generated based on the following inputs:

- **Age**: Numeric value (22–44)
- **Archetype**: One of 15 character archetypes (e.g., "Hero / Warrior", "Explorer / Seeker")
- **Profession**: A real-world job title (e.g., "Software Developer", "Chef")
- **City**: U.S. city for personalization (e.g., "Chicago", "San Francisco")
- **Message Type**: "Funny", "Motivational", or "Professional"

## Dataset Fields

- `age` (int): The individual's age.
- `archetype` (string): One of 15 character archetypes.
- `profession` (string): The profession of the individual.
- `city` (string): The city the individual is located in.
- `message_type` (string): Desired tone of message ("Funny", "Motivational", "Professional").
- `message` (string): Generated personalized message.

## Intended Use

This dataset is intended for training models that generate personalized messages based on personality, demographics, and tone. It can also be used for prompt engineering, chatbot personalization, or fine-tuning small language models.

## License

[MIT License](https://opensource.org/licenses/MIT)

## Citation

If you use this dataset, please cite:
@misc{archetype2025,
title={Archetype Messages Dataset},
author={Hana Elbatouty},
year={2025},
howpublished={\url{https://huggingface.co/datasets/hanaelbatouty/archetype-messages}}
}


