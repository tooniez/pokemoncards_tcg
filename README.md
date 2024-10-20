# Dataset Card for Pokemon Cards TCG

## Dataset Description

- **Repository:** [tooniez/pokemoncards_tcg](https://huggingface.co/datasets/tooniez/pokemoncards_tcg)
- **Point of Contact:** [Your contact information or GitHub profile]

### Dataset Summary

This dataset contains information about Pokemon Trading Card Game (TCG) cards, decks, and sets. It is designed to be used for training machine learning models to classify and analyze Pokemon cards.

### Supported Tasks and Leaderboards

- **Tasks:** 
  - Image Classification
  - Text Classification
  - Information Retrieval

### Languages

The dataset is primarily in English.

## Dataset Structure

### Data Instances

The dataset consists of three main components:

1. Cards: Detailed information about individual Pokemon cards.
2. Decks: Collections of cards forming playable decks.
3. Sets: Information about different Pokemon card sets.

### Data Fields

- Cards:
  - id: Unique identifier for the card
  - name: Name of the Pokemon or card
  - supertype: Type of card (e.g., Pokemon, Trainer, Energy)
  - subtypes: Subtypes of the card
  - hp: Hit points (for Pokemon cards)
  - types: Element types of the Pokemon
  - evolves_from: Name of the Pokemon this card evolves from
  - abilities: Special abilities of the Pokemon
  - attacks: Attacks the Pokemon can use
  - weaknesses: Elemental weaknesses
  - resistances: Elemental resistances
  - retreat_cost: Cost to retreat the Pokemon
  - converted_retreat_cost: Numeric value of retreat cost
  - set: Set the card belongs to
  - number: Card number within the set
  - artist: Name of the card artist
  - rarity: Rarity of the card
  - flavor_text: Descriptive text on the card
  - national_pokedex_numbers: Pokedex numbers for the Pokemon
  - legalities: Legal status in different game formats
  - images: URLs to card images
  <!-- - tcgplayer: Price information from TCGPlayer
  - cardmarket: Price information from Cardmarket -->

- Decks:
  - id: Unique identifier for the deck
  - name: Name of the deck
  - types: Types of cards in the deck
  - card_id: Unique identifier for each card in the deck
  - card_name: Name of each card in the deck
  - card_rarity: Rarity of each card in the deck
  - card_count: Number of copies of each card in the deck

- Sets:
  - id: Unique identifier for the set
  - name: Name of the set
  - series: Series the set belongs to
  - printedTotal: Total number of cards printed in the set
  - total: Total number of cards in the set
  - legalities: Legal status in different game formats
  - ptcgoCode: Code used in the Pokemon Trading Card Game Online
  - releaseDate: Date the set was released
  - updatedAt: Date the set information was last updated
  - symbol_image_source: URL to the set symbol image
  - logo_image_source: URL to the set logo image


## Dataset Creation

### Curation Rationale

This dataset was created to provide a comprehensive resource for Pokemon TCG enthusiasts, collectors, and researchers. It aims to facilitate machine learning projects related to card classification, price prediction, and deck analysis.

### Source Data

#### Initial Data Collection and Normalization

[Describe the process of data collection and any normalization steps]

#### Who are the source language producers?

The data is sourced from official Pokemon TCG information and community-contributed data.

### Annotations

[If there are any annotations in the dataset, describe them here]

### Personal and Sensitive Information

This dataset does not contain personal or sensitive information.

## Considerations for Using the Data

### Social Impact of Dataset

This dataset can contribute to the Pokemon TCG community by enabling research and tool development for card analysis and deck building.

### Discussion of Biases

[Discuss any potential biases in the dataset, if applicable]

### Other Known Limitations

[Mention any known limitations of the dataset]

## Additional Information

### Dataset Curators

[Information about the dataset curators]

### Licensing Information

[Specify the license under which the dataset is released]

### Citation Information

[If there's a specific way to cite this dataset, include it here]

### Contributions

[Information about how to contribute to the dataset, if applicable]
