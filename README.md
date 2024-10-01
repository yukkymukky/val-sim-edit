# How to Edit Valorant Simulator DB Values (Using an Extension)

You can edit the values in Valorant Simulator by accessing its local IndexedDB. This lets you customize the game to your liking! Here's a step-by-step guide:

### Steps:

1. **Install the IDB CRUD Extension**:  
   Get the extension from this [link](https://chromewebstore.google.com/detail/idb-crud-indexeddb-manage/olbigpjodejcmmdkafnhaphdblimjogg).

2. **Open Valorant Simulator**:  
   Create a game within the simulator.

3. **Access the IDB CRUD Extension**:  
   Open the extension from the top right of Chrome (under the puzzle icon).

4. **Refresh IndexedDB**:  
   Once the IDB CRUD extension is open, click the refresh button near `IndexedDB`. Your database should now appear with a name like: `ValSim-YOURUSER-YOURTEAM-v1-2024...`

5. **Open the Database**:  
   Click the arrow next to your database to expand it.
   
   ![DB Expansion](https://i.imgur.com/UCBhe2a.png)

6. **Find the 'Players' Section**:  
   You'll see many options, but we are focusing on the `players` section. Click it to access player data.

   ![Player Section](https://i.imgur.com/uHv9BJP.png)

7. **Search for Your Player**:  
   Use fields like `teamID`, or the `name` (case-sensitive) to locate the player you want to edit. In this example, we'll edit JohnQt's stats.
   
   ![Player Selection](https://i.imgur.com/Mzdo3Bm.png)

8. **Expand Player Data**:  
   Click the arrow next to the player's name. A panel should appear at the bottom. Expand it by clicking the arrow next to the number `0`. If you're in a later season, the number might be `1` or higher.

   ![Expand Player Data](https://i.imgur.com/6UIJdcK.png)

9. **Edit the Player's Values**:  
   You can now change different player attributes. Hover over any value and click the edit button, then save. For example, you can set stats, potential, growth, or even salary to custom values.
   
   ![Editing Values](https://i.imgur.com/USz6nTl.png)

   In this example, JohnQt's stats are set to 99, his potential is 99, his growth (development speed) is 99, and his salary is set to 0!

10. **Refresh the Game**:  
    Once you're done making changes, close the menu and refresh the page.

    ![Insane JohnQt](https://i.imgur.com/h5P2MJE.png)

    Now you have an insanely powerful JohnQt who costs nothing! LFGGG!!!
