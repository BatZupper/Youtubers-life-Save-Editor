# Youtubers-Life Save Editor

A simple and user-friendly save editor for Youtubers Life

## Description

This is an easy-to-use save editor designed for the average player. It allows you to edit your Youtubers Life save files effortlessly. no advanced knowledge required.
Future updates will include automatic patching and more intuitive editing tools, so you won’t need to know internal IDs to modify things like your house or other assets.

## Save Format

The save format is quite simple: each save file is a .tsv (tab-separated values) file compressed with GZIP.

## How to Use

1. Load your save file.

2. Make your modifications using the built-in text editor.

3. Save the file and reload it in the game.

## Contributing

Anyone is welcome to help! :D

## Project Story

Youtubers Life has always held a special place in my heart- I’ve spent around 91.2 hours playing it! When a friend of mine told me he had over 100 hours, I wanted to prove that I was the bigger YL1 fan, so I started this project.
At first, I was completely lost. I spent hours staring at a save file in my trusty hex editor, trying to make sense of it. Then I noticed something interesting. every save file started with H4sIA. It looked very familiar.
After digging a bit deeper, I realized it was actually a GZIP file disguised as a .yls save. I tried decompressing it… and it worked! I had a fully readable .tsv file that I could edit freely. That was the moment I managed to make my first successful modifications!
