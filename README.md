# Spotify Music Taste

Through its API, Spotify has a wealth of data linked to individual users making it a rich database for data and music lovers alike to explore their personal music. Using the [Spotipy package](https://spotipy.readthedocs.io/en/2.23.0_a/) I do some exploratory analysis on my own music data. As an avid user of the platform since 2013, and having changed accounts in 2015 for the prolongation of the student discount, I have almost 10 years of data to look at.

Here is an EDA of my music taste, with some possbible research questions to pursue: 

- Link to [Slide Deck](https://docs.google.com/presentation/d/1mlUmNVMOPBCQN56y6zr76MHRVZeaDx6FAFDvGbu-hW0/edit?usp=sharing)
- Jupyter Notebook in repository
  
The question I am most interested in exploring is why there was an increase in valence in 2022. Is this due to a shift in genre, key, or maybe mode?
![Valence](https://github.com/cameronmirh/SpotifyMusicTaste/assets/53825687/ed58248f-4438-4e9f-91f0-edd7fb7c843a)

Here you can see that 2022 was the only year that had exclusively pop genres in its top 5
![Genre](https://github.com/cameronmirh/SpotifyMusicTaste/assets/53825687/5379c51e-c797-4a29-ac97-0363427cd96f)

Generally, the genres from 2022 had a higher valence than did the genres of 2016 (which had the lowest overall valence than any other year)

<div align="center">
  <table>
    <tr>
      <td align="center"><b>2022</b></td>
      <td align="center"><b>2016</b></td>
    </tr>
    <tr>
      <td>
        <img src="https://github.com/cameronmirh/SpotifyMusicTaste/assets/53825687/64665060-2e43-4e4c-846f-397aecbf193c" alt="2022" width="300"/>
      </td>
      <td>
        <img src="https://github.com/cameronmirh/SpotifyMusicTaste/assets/53825687/eae54b27-cae2-4a98-b95b-5e67d25da55b" alt="2016" width="300"/>
      </td>
    </tr>
  </table>
</div>


A limitation of this study, however, is the fact that songs do not have individual genres in the API--only artists do. The genres for each song where the first genre associated with an artist.


