🐾 Pawkemon: A Real-Life Rescue Game
I’m building Animal GO because I think we can use the same mechanics that made Pokémon GO a hit to actually solve a real-world problem: stray animal welfare.

My plan is to create a game where community users help out local cat or dog in real life to earn rewards and points. 

The Gameplay Loop
As a user walks through the city, the app pings them when a stray is within 200m. 

The "ping" system isn't random; it’s powered by the community. When a user scouts and registers a new stray animal at a specific GPS location, it creates a Live Node on the map. Every other user who enters a 200m radius of that node will receive an automatic notification. This turns every registered animal into a "Quest Marker" that others can visit to provide care, feeding, or validation.

To turn a stray into a "Live Node" on the map, a user must perform a First Discovery. This is the most rewarded action in the game:

The Capture: The user takes a clear, real-time photo of the animal.
Labeling: The user identifies the species (Cat/Dog/Other), estimated age, and health status.
Naming: The user gives the animal a name

Users earn Karma Points by doing the actual work:

Registration : Completing a new registration earns the user 100 Karma Points.

Scouting: Finding a new stray and creating a profile (+25) or updating a photo (+5).

Daily Care: Feeding (+10), socializing/taming (+8), or giving a bath (+50).

Big Impact: Taking a pet to the vet (+70) or cleaning up a habitat/drain (+200).

The Synergy Bonus: If two users are within 10 meters of each other while performing a task, they both get a 1.5x Point Multiplier. I really want to encourage people to head out in teams.

Keeping it Honest
To stop people from "farming" points with fake videos, I’m building a peer-audit system. Users help each other by validating rescues—if a user is nearby, they can confirm a deed. I’m also adding "point decay" where unused currency eventually turns into XP (Experience). This keeps the economy moving and ensures only active rescuers have the most "spending power."

The Technical Plan
I’ll be honest: I’m a beginner in development, but I have a very clear vision for the architecture. I'm starting with a React Native (Expo) frontend and Supabase for the backend.

Geofencing: Using GPS to trigger local notifications and "Link" bonuses.

Media Handling: Uploading video/photo proof to a storage bucket for peer review.

Logic: A RewardEngine.ts to handle complex point calculations and synergy multipliers.

The Long-Term Vision (Optional/Future Phase)
I’m focusing on the game mechanics and the community first. Only once the game is mature do I plan to transition this into a full DePIN/DeApp.

DePIN: Turning every user's phone into a decentralized node for live animal data.

DeFi: Implementing smart contracts so donations go directly to the people on the ground with zero middlemen.

DAO: Eventually, I’ll step back and let the community vote on rules and how "Karma" is spent.
