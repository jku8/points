# points

#### Get NVM
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.31.0/install.sh | bash

#### Install NVM
* nvm install
* nvm use
* npm install

#### RUN CODE
node lib/index.js {input}

#### VALID INPUT Examples
* node lib/index.js 5x5 (1,2)
* node lib/index.js 5x5 (1,2) (3,4)
* node lib/index.js 3x3 '(1, 2)' '(3, 3)' '(2, 3)'

#### Output meaning
Given a grid size and some axis points map the movements and print out how many times they move and then drop at that given point
* N: north
* S: south
* E: east
* W: west
* D: drop
* 5x5 (1, 3) (4, 4) => ENNNDEEEND




#### TESTING
npm test