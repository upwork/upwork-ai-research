# UPHELD dataset

In total we collected complete evaluation labels for 400 turns stemming from 53 human written
conversations. This was transformed in turn-per-turn prediction.

Each predicted turn was evaluated by five human annotators, and each annotator judge labeled
between 1,220 and 1,230 conversations. We overall generated 12,291 sets of labels, or 36,873 labels.
The ground truth conversations consist of 5.2 turn pairs (user-assistant) or 10.4 dialogue turns in
average. The average length of the conversation history annotators analyzed was 560 characters and
the length of the judged turns was on average 245 characters

## Files

Data is provided in [Croissant](https://mlcommons.org/working-groups/data/croissant/) meta-data format.

The metadata JSON-LD file is [metadata.json](metadata.json).

Other files are individual labels by each annotator.

### Verification datasets

Verification datasets derrived from [llm-arena](https://huggingface.co/datasets/lmsys/chatbot_arena_conversations) and [topical-chat](https://github.com/alexa/Topical-Chat) datasets can be found in [additional_resources](https://github.com/upwork/upwork-ai-research/tree/upheld/data/upheld/additional_resources) folder.
They are uploaded as individual csv files for each annotator.  


