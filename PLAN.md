# D3: temp title

## Game Design Vision

Currently Undecided, set up of basic mechanics

## Technologies

- TypeScript for most game code, little to no explicit HTML, and all CSS collected in common `style.css` file
- Leaflet library to handle map display
- Deno and Vite for building
- GitHub Actions + GitHub Pages for deployment automation

## Assignments

### D3.a: Core mechanics (token collection and crafting)

Key technical challenge: Can you assemble a map-based user interface using the Leaflet mapping framework?
Key gameplay challenge: Can players collect and craft tokens from nearby locations to finally make one of sufficiently high value?

#### Steps

- [x] delete everything in main.ts
- [ ] put a basic leaflet map on the screen
- [ ] draw the player's location on the map
- [ ] draw a rectangle representing one cell on the map
- [ ] add token data to the cell
- [ ] use loops to draw a whole grid of cells on the map
- [ ] ensure that loops are consistent between loads/refreshes
- [ ] allow players to pickup tokens in cells
- [ ] display token data in inventory
- [ ] allow players to combine inventory token with equal token on map
