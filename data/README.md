# Spotify Dataset

## About the Dataset
This dataset is collected from Spotify's API using two Python scripts to extract both popular and non-popular songs along with their associated audio and descriptive features.

- **Descriptive Features** provide metadata about the track, such as artist name, album name, and release date.
- **Audio Features** are derived from Spotify's audio analysis and describe musical attributes such as tempo, danceability, and energy.

The dataset combines both feature types for analysis and experimentation.

## Features

### Audio Features
| Feature          | Description  |
|-----------------|--------------|
| **Energy**      | A measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. |
| **Tempo**       | The speed of a track, measured in beats per minute (BPM). |
| **Danceability** | A score describing how suitable a track is for dancing based on tempo, rhythm stability, beat strength, and overall regularity. |
| **Loudness**    | The overall loudness of a track in decibels (dB). Higher values indicate louder tracks overall. |
| **Liveness**    | The likelihood of a track being performed live. Higher values suggest more audience presence. |
| **Valence**     | The overall musical positiveness (emotion) of a track. High valence sounds happy; low valence sounds sad or angry. |
| **Speechiness** | Measures the presence of spoken words. |
| **Instrumentalness** | The likelihood a track contains no vocals. Values closer to 1.0 suggest solely instrumental tracks. |
| **Mode**        | Indicates the modality of the track. |
| **Key**         | The musical key, represented as an integer from 0 to 11, mapping to standard Pitch class notation. |
| **Duration_ms** | The length of the track in milliseconds. |
| **Acousticness** | A confidence measure of whether a track is acoustic (1) or not (0). |

### Descriptive Features
| Feature                    | Description  |
|----------------------------|--------------|
| **Track Name**             | The name of the track. |
| **Track Artist**           | The artist(s) performing the track. |
| **Track Album Name**       | The album in which the track is featured. |
| **Track Album Release Date** | The release date of the album containing the track. |
| **Track ID**               | A unique identifier assigned to the track by Spotify. |
| **Track Album ID**         | A unique identifier for the album. |
| **Playlist Name**          | The name of the playlist where the track is included. |
| **Playlist Genre**         | The main genre associated with the playlist (e.g., pop, rock, classical). |
| **Playlist Subgenre**      | A more specific subgenre tied to the playlist (e.g., indie pop, punk rock). |
| **Playlist ID**            | A unique identifier for the playlist. |
| **Track Popularity**       | A score (0–100) calculated based on the total number of streams in relation to other songs. |

---

