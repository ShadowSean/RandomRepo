# Interactive Lab Assignment
Sean Nwabuoku, 10092748

Post Process & Daytime Changer

Within this game I made use of the singleton design within Unreal Engine by using a game instance that manages the 
post process settings on the player camera on top of being able to manage the directional light settings within the game world.
I made a custom game instance that only allows itself to be loaded into the world so that no other instance can exist within the game world.
The custom game instance has multiple functions that enable the changes on the player camera and the directional light within the world space. I then now reference these
inside the third person character blueprint to create special events for each action. Once I made the events I went into the level blueprint to enable these events by casting
to the third person player character and on specific keys being pressed, the events are enabled. This pattern is a very good choice for the associated functionality
as it can be expanded into much more. For example if I wish to make a settings widget blueprint, I can call these post process and directional light events through button click,hover
events or slider events. If I want some kind of data to be changed on the player within the world using settings, the current setup I have can easily be translated into something
of that scope.

# In Game Screenshots
<img width="1912" height="857" alt="image" src="https://github.com/user-attachments/assets/94e5fac4-97b7-4813-8a2c-38abb14683ca" />
<img width="1907" height="833" alt="image" src="https://github.com/user-attachments/assets/99593aa3-08cc-4f77-b34b-76e91964ffdc" />
<img width="1919" height="979" alt="image" src="https://github.com/user-attachments/assets/c3f59815-478b-4582-af29-080fab85b911" />
<img width="1919" height="878" alt="image" src="https://github.com/user-attachments/assets/b6f02a05-6a9d-4ebf-99ae-49e4095e301b" />
<img width="1919" height="975" alt="image" src="https://github.com/user-attachments/assets/47a26c3e-1ca6-48f1-9d5a-529872c6a30b" />


# Third Person Character blueprint events
<img width="1285" height="199" alt="image" src="https://github.com/user-attachments/assets/52ea9914-8426-4c3b-ac31-30339a226f78" />
<img width="1691" height="677" alt="image" src="https://github.com/user-attachments/assets/700e55ea-4681-49ad-bc52-30c7fe05336a" />

# Custom Game Instance Functions
<img width="1919" height="818" alt="image" src="https://github.com/user-attachments/assets/bd6e4721-e035-4f18-b5d6-2e2db924b4cd" />
<img width="1919" height="827" alt="image" src="https://github.com/user-attachments/assets/79fe1ff5-8df0-4599-a6ae-4eeb0def4965" />
<img width="1919" height="810" alt="image" src="https://github.com/user-attachments/assets/ac4f215e-ab87-4f2e-aaf1-39a0221bc0e3" />
<img width="1919" height="853" alt="image" src="https://github.com/user-attachments/assets/3ab8e1a7-2712-483e-806a-8cd2706320dc" />
<img width="1919" height="812" alt="image" src="https://github.com/user-attachments/assets/2c14be1b-4fa1-4f71-a113-4221f8aed1d4" />

# Level Blueprint
<img width="1919" height="977" alt="image" src="https://github.com/user-attachments/assets/948405fb-8e20-435e-a906-a06a2cb265bf" />
<img width="752" height="177" alt="image" src="https://github.com/user-attachments/assets/9ddf14ca-d77e-494e-8124-b4681d5ece65" />

# Widget Blueprint displaying controls
<img width="1919" height="844" alt="image" src="https://github.com/user-attachments/assets/85349699-1e87-4968-ba06-44d350920099" />
