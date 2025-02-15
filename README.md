This is a fork of: https://github.com/jas3333/GPT-Helper and is updated to work with `typescript` and uses `@mui` material design components and works on mobile. It was largely modified using GPT/ChatGPT.

## GPT Prompt Engineer

This app is an interface to the GPT3 API. **It isn't ChatGPT nor does it use the Chatgpt api**.
It was made as a second option to ChatGPT, due to the ChatGPT often being overloaded.

## How to use it:

- Automatically prefix questions with your own personas/prompts
- Prompt-engineering
- ?
- Profit

Remember this is **NOT** ChatGPT and won't work the same, you should reset the prompt when asking different questions, it is not very good at maintaining a threaded conversation.

### To install:

You need an Openai account and an API key

git clone the repo:

```
git clone https://github.com/TrySpace/GPT-Helper
cd GPT-Helper
npm install
```

### To run:

You will need to setup a .env file in the client directory. Make sure the file is named `.env` and nothing else.
`something.env` will not work.

```
REACT_APP_OPENAI_KEY=yourkey
```

Then run `npm start`, it should automatically open the page on port `3000`

## Configure Personas

You can edit `./config/personas.ts`

### Todos

- ~Nicer loading~
- ~Toggle dark/light theme~
- ~Make PromptController into sidebar~ or popover
- ~Remember last persona & model~
- Fix Chat overflow
- Better prompt insight
- Updating 1 Question and see the diff of the Answer
- Local persona edit
- Tweak Response component layout?
- Fix build not resolving correct paths
- Update to GPT 4?
