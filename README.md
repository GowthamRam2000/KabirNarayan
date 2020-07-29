### Hi there 👋
wassup , I created this readme as an iceBreaker come up say hi !! if you have issues theres a icon at the top left ,you can create some issues storm there  


- 🔭 I’m currently working on ... creating a solution to monitor traffic using satellite images in india ,creating a website for myself ,custom kernel bootImg rewritten in rust 
- 🌱 I’m currently learning ... languages i'm good at are python ,java ,c,html,css
                                languages i'm learning to work with rust ,dart ,c++,javascript,
                                frameworks that i am interested in flutter ,react ,react Native
                                sometimes i dabble in philosophy & religion and their interconnectness
                                
- 👯 I’m looking to collaborate on ...anything interesting
- 💬 Ask me about ...university life , psychology
- 📫 How to reach me: ...gowthamm161@gmail.com
- 😄 Pronouns: ...yeah none
- ⚡ Fun fact: ...Ars long, vita brevis means The Art is Long but life is short 

oh yes there's also have redudant website for which I overpayed FOR hosting because it seemed cool at the time ,Also note sometimes I overEngineer stuff prime example would be this readme 

import { GitHubNowPlaying } from 'github-now-playing';

const nowPlaying = new GitHubNowPlaying({
 token: process.env.46ba849b1c41c0a6fc93fa16d1311b8790038b69,
});

// Create a new source to retrieve the track that is currently playing
const spotifySource = new GitHubNowPlaying.Sources.Spotify({
 // wait time in milliseconds between checks for any track changes
 updateFrequency: 1000,
});

// Make sure a source is set before calling listen()
nowPlaying.setSource(spotifySource);

// Don't forget to handle the error event!
nowPlaying.on(GitHubNowPlaying.Events.Error, error => {
  console.log('something went wrong');
});

// Listen to any track changes and update the profile status accordingly.
nowPlaying.listen();

// Don't forget to stop reporting any track changes when the process exists.
process.on('SIGINT', () => {
  // Calling the stop() method will clear the profile status.
  nowPlaying.stop()
});
