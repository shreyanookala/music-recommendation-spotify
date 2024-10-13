
# Music Recommendation System using Spotify API

This project demonstrates a hybrid music recommendation system built using Spotify's API. Given an input song, it returns a list of recommended songs based on several factors like popularity and other features.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [How to Run](#how-to-run)
- [Example Usage](#example-usage)
- [Dependencies](#dependencies)
- [Output](#output)
- [Contributing](#contributing)

## Features

- **API Authentication**: Uses Spotify's Client ID and Client Secret to authenticate and retrieve an access token.
- **Hybrid Recommendation**: Returns a list of songs similar to the input song.
- **Spotipy**: Leverages the Spotipy library to interact with the Spotify API.

## Prerequisites

- Python 3.7+
- Spotify Developer Account (to get your own Client ID and Client Secret)
- Spotipy Library (`pip install spotipy`)

## How to Run

1. Clone this repository.
2. Open the notebook in Jupyter or any compatible environment.
3. Replace the `CLIENT_ID` and `CLIENT_SECRET` in the notebook with your own.
4. Run the cells to obtain song recommendations.

## Example Usage

```python
input_song_name = "I'm Good (Blue)"
recommendations = hybrid_recommendations(input_song_name, num_recommendations=5)
print(recommendations)
```

## Dependencies

- requests
- base64
- spotipy

## Output

The system will provide a list of recommended songs based on the input song. Example output:

```
Hybrid recommended songs for 'I'm Good (Blue)':

                     Track Name                                     Artists
3                       KEEP UP                                     Odetari   
4  It's Not Right But It's Okay                            Mr. Belt & Wezol   
1                         REACT  Switch Disco, Ella Henderson, Robert Miles   
2                 Where You Are                          John Summit, HAYLA   
0                          BOTH                      Tiësto, 21 Savage, BIA   
```

## Contributing 

Feel free to submit issues or pull requests.Any contributions are welcome!

