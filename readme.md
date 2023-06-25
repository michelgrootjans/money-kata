# Test-driven development by example

## Requirements

Come up with a design that can add and multiply multiple currencies given the necessary exchange rates. For example:

given USD:EUR 2:1

| Instrument | Shares | Price         | Total          |
|------------|--------|---------------|----------------|
| BEL 20     | 100    | 3500 EUR      | 350000 EUR     |
| NASDAQ     | 20     | 15000 USD     | 300000 USD     |
| AEX        | 400    | 750 EUR       | 300000 USD     |
|            |        | **Total**     | **800000 EUR** | 

## Getting started
You can start working in multiple technologies:
- java: Initialize the project with `gradle wrapper`. Open it in your favorite IDE.
  - create `src/java/test/MoneyTest.java` and start from there
- kotlin: Initialize the project with `gradle wrapper`. Open it in your favorite IDE.
  - create `src/kotlin/test/MoneyTest.kt` and start from there
- javascript: `npm install` or `yarn start`
  - create `money.spec.js` and start from there
- typescript: `npm install` or `yarn start`
  - create `money.spec.ts` and start from there