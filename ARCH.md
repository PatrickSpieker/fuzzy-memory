
## Data model
- there is always one deck loaded
- the deck is a list of cards
  - cards have 2 sides, Side A and Side B
- There are 2 modes: edit and quiz
- Decks can be imported and exported as JSON files

## Tooling / Deployment / etc. 
- Want to use Typescript; azdavis makes the good point that maybe I shouldn't
- Vanilla as hell - TS -> JS, CSS, HTML

### Deployment Instructions
```
python3 -m http.server
```

# Scratch
All this needs to be extremely fast and like glass; super smooth. 

Basic happy path
- create a card 
- switch to quiz mode 
- run the quiz
- export the deck


