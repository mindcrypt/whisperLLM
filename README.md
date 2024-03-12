# WhisperLLM: Evading network security and censhorship by stegotexts

Over the last 10 years, many threat groups have employed stegomalware or other steganography-based techniques to attack organizations from all sectors and in all regions of the world. Some examples are: APT15/Vixen Panda, APT23/Tropic Trooper, APT29/Cozy Bear, APT32/OceanLotus, APT34/OilRig, APT37/ScarCruft, APT38/Lazarus Group, Duqu Group, Turla, Vawtrack, Powload, Lokibot, Ursnif, IceID, etc. To mitigate the impact of these attacks different proposals have been published. In Blackhat USA 2022 and BH ASIA 2023 we released the [Stegowiper](https://github.com/mindcrypt/stegowiper) tool that tries to reduce the success of these campaigns.

However, offensive capabilities are necessary in many scenarios and in some of them are related to enhanced privacy capabilities and censorship-resistant mechanisms.

This tool makes use of LLM to generate stegotexts in various languages (e.g., English) to hide useful information that may go unnoticed. Due to the nature of natural language texts and their wider dispersion, this can be an interesting approach and more difficult to override.

## Threat model

## How works. How much information can be hidden?


## Usage & Parameters


## Future work. Doing

We have studied numerous LLMs and currently the one that gives the best results is GPT-4, which is the one we use in the tool. Currently, we are implementing Mixtral and Llama2 in the tool to have LLM models that can be run locally.
