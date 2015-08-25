# Open Data Board Game Instructions

In this game, you and your fellow players run companies creating tools using data. Your goal is to create the most tools.

## Data

Data looks like this:

<img src="tiles/transport-closed.png" height="48">

There are six kinds of data. Each is represented by a different colour tile.

<table>
<tr><th>Tiles<th>Data<th>Impact
<tr><td><img src="tiles/product-closed.png" height="48"> <img src="tiles/product-open.png" height="48"><td>Product<td>Economic
<tr><td><img src="tiles/transport-closed.png" height="48"> <img src="tiles/transport-open.png" height="48"><td>Transport<td>Economic
<tr><td><img src="tiles/geography-closed.png" height="48"> <img src="tiles/geography-open.png" height="48"><td>Geography<td>Environmental
<tr><td><img src="tiles/weather-closed.png" height="48"> <img src="tiles/weather-open.png" height="48"><td>Weather<td>Environmental
<tr><td><img src="tiles/democracy-closed.png" height="48"> <img src="tiles/democracy-open.png" height="48"><td>Democracy<td>Social
<tr><td><img src="tiles/health-closed.png" height="48"> <img src="tiles/health-open.png" height="48"><td>Health<td>Social
</table>

Each tile represents a dataset. For example, a Transport tile might represent data about bus timetables or the locations of rail stations.

Over the course of the game, you and others place tiles to create the **data infrastructure**. A data infrastructure looks like:

[data infrastructure]

Within the data infrastructure, individual datasets can be closed or open. As the player placing data tiles, you can choose whether to place the tile as **open data** or **closed data**.

 **Closed data** looks like:

<img src="tiles/health-closed.png" height="48">

Only the player who has placed **closed data** can legally use that data to build tools (but see Hacking, below). Players cannot place their data tiles next to closed data that they do not own.

**Open data** looks like:

<img src="tiles/health-open.png" height="48">

Any player can use **open data** to build tools.

Counters on the tiles indicate who is using the data in the **data infrastructure**.

## Tools

You can build tools by linking different kinds of data together. Each tool that you can build is represented by a card. For example:

<img src="instructions/tool-card.png" width="525">

This tool uses transport, weather and location data. Perhaps it is an application that helps people get home by an appropriate route depending on the weather: if it's sunny, it recommends they walk or cycle; if it's raining, it will help them get a taxi.

During your turn, you can build new tools by matching the data shown on the card to the data that's available in the **data infrastructure**. The data in the **data infrastructure** must have exactly the same configuration as the picture on the card.

## The World

The world is in a state of flux. The **world board** shows how healthy the world is socially, environmentally and economically.

<table width="100%">
<tr>
<th style="width: 33%; text-align: center">Social</th><th style="width: 33%; text-align: center">Environmental</th><th style="width: 33%; text-align: center">Economic</th>
</tr>
<tr><td style="text-align: center"><img src="world-board/Social.png" height="48"></td><td style="text-align: center"><img src="world-board/Environmental.png" height="48"></td><td style="text-align: center"><img src="world-board/Economic.png" height="48"></td></tr>
</table>

Each of these scores varies from 0 to 8. 8 represents utopia. 0 represents complete social, environmental or economic collapse. **If any score gets to 0 the game is over; everyone loses.**

Building tools helps the world. When you build a new tool, you may have a social, environmental or economic impact that increases one of the scores by one. You can choose which type of impact you have depending on the types of data that are used by the tool.

For example, if you build the tool:

<img src="instructions/tool-card.png" width="525">

you can choose to either have an economic or an environmental impact. These icons are highlighted on the card.

### Events

Each turn, something happens in the world. These are represented by **event cards**, which look like:

<img src="instructions/event-card.png" width="525">

Events alter the world scores. They can add to a world score or (more frequently) reduce the score.

## Set Up

1. Set up the **world board**. Set each of the social, environmental and economic scores to 3.

2. Shuffle and place the **event cards** in a stack.

3. Place the **data tiles** in the bag.

4. Select one **data tile** at random from the bag and place it as **open data** in the centre of the table. This will be the first piece of **data infrastructure**, around which you start the game.

5. Each player chooses a set of coloured token, called **counters**.  These **counters** are used to identify data you own within the **data infrastructure**, and which data you are using - **open data** and **closed data** - to build your tools.

6. Each player picks one **data tile** at random from the bag and places it within the **data infrastructure** connected to the central **open data** tile. This first **data tile** must be placed as **closed data** within the **data infrastructure**. Add a **counter** on top of your **closed data**, to signify ownership.

7. Shuffle the pack of **tool cards** and deal eight **tool cards** face down in front of each player. Place the remaining **tool cards** back in the box. Each player takes two **tool cards** into their hand.

## Turn Taking

Your hand consists of a number of **data tiles** and **tool cards**. When it is your turn:

1. Select a **data tile** at random from the bag to join your hand.

2. Play any **tool cards** that you want to play. You may play any number of **tool cards** during your turn; these remain face up in front of you to demonstrate your success. Play an **tool card** by:

   a. placing the **tool card** on the table so that it is visible to everyone

   b. placing **data tiles** from your hand needed to complete the tool, either as **closed data** or as **open data** to expand the **data infrastructure**

   c. placing your tokens on all the data tiles that are used to create the tool

   d. increasing a score on the **world board** based on the type(s) of **data tile** that you have used to build your tool

3. Take a new **tool card** from the pile in front of you.

4. Take a new **event card** from the communal pile and adjust the **world board** accordingly.

### Negotiation

During your turn, you may open data that you own in the **data infrastructure** by flipping over the **data tile** to turn it from **closed data** to **open data**. (You cannot turn data from open data to closed data.)

During your turn, you may negotiate with any other player. You can try to persuade other players to:

  * give you a **data tile**
  * give you a **tool card**
  * open data in the **data infrastructure**

You will usually have to do one of these things in exchange. Players cannot negotiate with each other unless it is their turn.

You can choose what to show other players of your hand. You may play with an open hand, so that everyone can see what you have and what you need. You may play with an open hand of tools but hide which data you have. You may show some tools but not others. It is up to you.

### Hacking

When you play a **tool card**, you may only legally use data to create your tool if that data is:

  * **open data**
  * **closed data** that you **own** (has your counter on it)

If there is some **closed data** that you want to use to build your tool and the player who **owns** that data is not paying attention, you may try to build the tool using that data. This is known as **hacking**.

If you manage to build a tool including placing your token on **closed data** owned by someone else, you have **hacked** that data and are then able to use it for further tools, or open it up, exactly as if you were the original owner.

The original owner may stop you from **hacking** their data at any point up to you adjusting the **world score** as a result of building the tool.

## Ending the Game

The game ends in three scenarios:

1. The **world score** on any impact measure reduces to zero. Everyone loses.

2. The **world score** on all three impact measures increases to eight. Everyone wins.

3. Any player uses all the **tool cards** from their hand, and there are no more **tool cards** in their pile. The player who has built the most tools wins.

## Example of Play

Ellen has the following cards in her hand:

<img src="instructions/hand.png" width="525" />

The data infrastructure looks like this:

The world score looks like this:

She draws a blue data tile and realises that she can place it to build the first of the tools in her hand. However, doing this would not help the economy, which is in bad shape. If she rolls a 5 or 6 on the dice, it could be game over!

Ellen could place her second card, which would enable her to increase the economy score, if she could use James' yellow data. She asks him to open up that yellow data so that she can use it and offers the blue data that she has in exchange.

James takes the deal. He opens up his yellow data, leaving the data infrastructure like this:

Ellen plays the second of her tool cards. She places her tokens on the three datasets that she uses. The data infrastructure looks like:

Ellen choses to increase the economy score. The world score looks like:

Then Ellen rolls the dice. It's a 6! Ellen reduces the economy score again: it's a good thing she managed to play that application. If she hadn't, the game would be over.
