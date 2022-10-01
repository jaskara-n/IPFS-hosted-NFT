Hi folks,

this is an advanced ipfs hosted nft(ERC421 standard token - using openzepellin)

its functions are:

Mint a random NFT using Chainlink VRF to get a random number with added mocks to test on a local node
pug,shuba inu, st.bernard are the types of NFTs with different rarities.
pug super rare.
shiba inu lesss rare.
st bernard most common.
users have to pay to mint an nft.
Only owner of contract can withdraw eth.
if development chains are used, we can use mocks for the chainlink aggregators,etc.
using pinata to host images on ipfs.(check utils/uploadToPinata.js).
it also has a verify script.
