There is a detailed description over on [my website](https://blake-bollinger.com/2020/05/26/building-a-neural-network-to-play-snake/)!

# Welcome to SnakeAI

Snake AI is a swift playground that contains a neural network built to play the classic game Snake

The neural network has no dependencies and is built in pure Swift 5 for fast and efficient training and inferencing. Can be trained AT RUNTIME in <1sec

## How to Run:

1. Download/Clone repo
2. Open Main.playground in Xcode (Tested in v11.5)
3. Compile (May take time because of Swift type-checking)
4. Run

## The repository includes:

A swift playground with the [core Snake functionality](/Main.playground/Sources/Snake%20Game)

[A custom 5x100x100x4 neural network](/Main.playground/Sources/Neural%20Network) that is trained at runtime

\~30 mins of generated Snake gameplay as [training data](/Main.playground/Sources/Neural%20Network/TrainingData.swift)

### Current High Score: 17

## Todo:

- [ ] Add more training data

## See More:

Some of the neural network included in SnakeAI draws from SwiftAI. Check out their repo [here](https://github.com/Swift-AI/Swift-AI)
