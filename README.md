# NFT Minting Script
# Overview
This script provides a simple implementation for minting NFTs (Non-Fungible Tokens). It allows you to create NFTs with specific metadata, store them, list all minted NFTs, and get the total number of NFTs created.

# Features
Mint NFT: Create an NFT with specific metadata.
List NFTs: Display all the NFTs along with their metadata.
Total Supply: Get the total count of NFTs minted.

# Variables
NFTs: An array to store the minted NFTs.

# Functions
# mintNFT

This function takes in three parameters (name, id, and balance) to create an NFT object with these properties and stores it in the NFTs array.


# listNFTs

This function lists all the NFTs stored in the NFTs array. It uses forEach to iterate through the array and log the details of each NFT.


# getTotalSupply

This function logs the total number of NFTs minted by returning the length of the NFTs array.
