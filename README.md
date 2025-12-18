
Vibe Coding UI Starter
===================

## STEP 1: Preparing the Design
Before we write any code, we need a design mockup to work from.
This workflow starts from one image of a design mockup. This means that it'll work with any design you throw at it.

Here are a few options to get you started with a design.

### Option A: Generate with AI
You can use ChatGPT or Gemini's Nano Banana Pro to generate design concepts. Both OpenAI's and Google's image models are good enough to generate entire mockups these days. I've written design prompts in the past that work well for this—the key is being specific about the style, colors, and components you want.

[Here's a template prompt you can use to generate UI mockups with AI](./prompts/mockup.md)

You can add custom instructions on style, colors, layout and content and attach the prompt as context.

For example:
```
Use the attached specification as a template to generate a design brief.

Your task is to write a new specification for a fintech app called "Roobin Mood".
Rewrite it based on the following requirements:
- Style: Skeuomorphic, modern, deep shadows, glass, soft colors.
- Colors: Green accents, black background, white text.
- Layout: 3-column layout, with a sidebar on the left and a main content area on the right.
- Content: A dashboard with a sidebar navigation and a main content area.
- Components
  - A line chart showing account balances
  - A table showing past transactions
  - A card showing the latest news
  - A card showing total gains/losses

<paste mockup design brief from above here>
```
To check if this looks right, you can prompt AI to generate images based on the new specification before you jump into coding.

| Check the [AI design style reference](./prompts/AI_DESIGN_STYLE_REFERENCE.md) for more ideas on how to write this prompt.

### Option B: Use an image as input
Most commonly, you'll have a mockup that you would like to code up.
If you don't have a design and just want to make a prototype real quick, you have a few lazy options:

- Use Mobbin for entire flows
- Get a design from Dribbble
- Take a screenshot of an app that you like
Attach it as the context for the prompt, and then make sure to specify the style, colors, layout and content in the prompt as shown above. Attach it as the context for the prompt, and then make sure to specify the style, colors, layout, and content in the prompt as shown above.


### What Makes a Good Reference Design?
Look for designs that have:

- Clear visual hierarchy: Headers, cards, sections are obvious
- Consistent spacing: Not chaotic or random
- A defined color palette: Usually 2-3 main colors
- Real UI elements: Charts, tables, cards, navigation
- The better the reference, the better the output.

## STEP 2: Generate the Design Brief 

This is where the first key part comes in.

The design needs to be converted into something the AI coding agent can use. AI coding has come a long way, so it will generate something even from a bad prompt. However, generating a good design that matches our intent requires a lot more detail and specificity. Otherwise, AI will just do guesswork and you'll end up with the classic purple design.

Through much experimentation, I've found that converting the design to a JSONC format (JSON with Comments) gives the most accurate results. This structured format helps AI understand exactly what to build.

[Here's a template prompt you can use to generate a design brief from a mockup](./prompts/brief.md)

The only part you need to change is the first line: **This is a dashboard of a modern fintech app called Mevolut**. Write a concise description of the app and the dashboard you're building and then fire off the prompt.

Note: ChatGPT is great at this, but you can also use Gemini to generate the brief.

The output should be two code blocks: one for the design brief and one for the JSONC design specification.
Make note of both as you'll need them in Step 3.

## Step 3: Generate the Code
With the design brief and the starter kit in hand, it's now time to generate the code.
Let's head over to Cursor and implement the design.you can also use Claude Code or Windsurf to generate the code. The starter kit + prompt below should work fine with other AI coding tools, too.

### The Implementation Prompt
Even though the specification generated in Step 1 is quite detailed, we need to prompt the AI coding agent with a few more important requirements, such as:

- responsive design
- dark mode support
- no magic strings
- design system usage
Without this, you'll likely get a lot of hardcoded values that are hard to change or maintain.

[Here's the prompt template you can use to generate the code](./prompts/implem.md)

## Installation

```bash
bun install
```

## Development

First, run the development server:

```bash
bun run dev
```

## Build

To build the site for production, run the following command:

```bash
bun run build
```
