# Cadence — QBR deck creator

Turn a few notes about a customer account into a presentation-ready Quarterly Business Review deck.

**[Live demo](#)** ← replace this link with your GitHub Pages URL once it's live

---

## What it does

I spent a couple of years in customer success, and the QBR was always the same grind. You have all the context in your head, but building the deck from scratch every quarter eats an afternoon you don't have. The hard part was never the slides. It was turning a pile of account notes into a clear story.

So I built a tool that does that part. You give it the basics about an account:

- Who the customer is and what quarter you're reviewing
- What they're trying to achieve with the product
- How adoption and usage are going
- Wins from the quarter
- Any risks or challenges

It turns that into a full QBR deck: a title slide, an agenda, an executive summary, and a slide for each section with a clear headline and bullet points. You can flip through it on screen and download it as a real PowerPoint file to edit or present.

## How it works

The core idea is simple. QBR content is mostly the same shape every time: goals and progress, adoption, wins, risks, priorities for next quarter, next steps. The tool takes your raw notes and organizes them into that structure with a clean headline and tight bullets per slide, then lays it out as slides.

The live version I use is powered by AI to generate the deck content from whatever notes you type. This public demo runs on a set of built-in example accounts across a few different industries, so anyone can open it and see the kind of deck it produces without any setup.

## Built with

- Plain HTML, CSS, and JavaScript, no framework
- [PptxGenJS](https://github.com/gitbrent/PptxGenJS) for the PowerPoint export
- The AI generation in the private version uses the Anthropic API

## Why I built it

I wanted something that turned the annoying, repetitive part of the job into a few minutes instead of an afternoon, and I wanted to build it myself rather than wait for a tool to do it. It also gave me a way to show what I care about in customer success work: getting to a clear story fast, and being honest about what's going well and what isn't.

## Notes

The public demo shows example accounts. The version that generates decks from your own notes needs an AI key, so it isn't wired into this public page for safety reasons. If you want to run that version, get in touch.

---

Built by Safi Siddiqui.
