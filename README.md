## OldPaintingValue 

This smart contract calculates the value of old paintings based on their creation year and the current year. Additionally, it includes a function related to a prize awarded to the artist. Here's a simple explanation:

### Contract Overview:

The contract is named `OldPaintingValue`.

### Constants:

- `baseValue`: The base value assigned to a painting, set at 100 units.
- `annualIncrement`: The annual increment percentage, set at 5%.

### Functions:

#### 1. `calculatePaintingValue`:

- **Parameters:**
  - `paintingYear`: The year the painting was created.
  - `currentYear`: The current year for valuation.
- **Returns:** The calculated value of the painting.
- **Conditions:**
  - Requires that the `paintingYear` is before 1970 for a specific valuation (50 units).
  - Asserts that the `currentYear` is not beyond 2024.

#### 2. `PrizeWon`:

- **Parameters:**
  - `isArtistAlive`: A boolean indicating whether the artist is alive or not.
- **Conditions:**
  - Requires that the artist is not alive for the awarding of a prize.
  - Reverts with a message indicating a posthumous award.

### License:

This smart contract is licensed under the MIT License.

## Auhtor 

Hithesh

hitheshreddy002200@gmail.com
