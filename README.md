<img width="637" alt="image" src="https://github.com/Zapper-fi/chainchat/assets/6855274/1fd3e189-f59c-4575-8fb1-3b4e1295936c">

# Chainchat: Onchain Group Chats 
Blockchains aren't just about shifting economic power, but also about reshaping human coordination. Throughout history, shared incentives have driven human collaboration. Blockchains, in this regard, stand as a novel platform, allowing the design of positive-sum games that bolster human connection.

# The Social Network Dilemma
Early in their life cycle, most social networks exude a strong sense of community. However, as they expand, these networks begin to fragment. The primary culprit? Incentives. Rather than rewarding genuine connection, social networks increasingly prioritize reach and engagement. 

This optimization quickly morphs into a rat race for popularity. The social dynamics of high school, where one strives for popularity, often at the expense of their authentic self, re-emerge on a grander scale. As these platforms surpass even the restrictive confines of high school, they further damage our sense of self. 

Suddenly, you're in a feedback loop that continually reinforces a manufactured identity. There’s nobody from high school to give you a reality check. Over time, the very fabric of society erodes, as the connecting nodes only connect us to the extent of our fakeness. We find ourselves ensnared in a negative-sum game. 

# The Escape
The disillusionment with modern social networks grows year over year. People are increasingly searching for genuine connection, which the incumbents no longer provide. The future lies in social networks that:
- Promote positive-sum games through shared incentives.
- Prioritize the quality of connecting nodes.

# Overview
Introducing Chainchat: an onchain solution for group discussions. Here, group chats are termed "channels." To join a channel, one must buy a share in the channel. To leave a channel you must sell all your shares in that channel. You can buy and sell multiple shares. You only need one share to be a member of the channel. The pricing mechanism for shares follows a bonding curve.

Each transaction incurs a 5% fee, which is added to the channel's fee pool. These fees can be proportionally withdrawn by shareholders based on their stakes at any time.

At its core, Chainchat aims to:
- Encourage value-driven conversations. By bringing value, you enhance your stake and others'. A high-quality channel, marked by insightful discussions, naturally becomes more valuable.
- Connect individuals with shared interests. Assigning economic value to a passion signals genuine interest, and finding those with similar valuations can catalyze impactful change in the world.

# Chainchat & Information Markets
Traditionally, information markets have faced a number of inefficiencies. While vast reach was achieved on traditional platforms, they often became sources of overwhelming noise, where information got diluted and popular narratives, not always accurate, dominated. This has been the case for “Crypto Twitter”, which often ends up, in many instances, being an unreliable information market, due to the nature and complexity of its algorithm. It’s not uncommon for new investment opportunities to mark a local top once they reach their apex of their crypto twitter engagement. 

Chainchat brings a transformative approach to this. By merging blockchain's transparency with private group interactions, it ensures a higher signal-to-noise ratio. The introduction of economic stakes in these private channels acts as a natural filter, sidelining non-committal noise and elevating genuine, valuable exchanges.

# Messaging Interface
The messaging UI is a completely separate piece that sits atop the smart contract. To view messages in a channel, you must be a member of the channel. The openness of Chainchat ensures anyone can build their own messaging service on top of it, this is simply its first client. We decided to unbundle both the protocol (channel ownership registry) and the messaging service, to allow for more flexibility and client diversity. 

Some key chat features include tagging addresses, tokens, and NFT collections. 

Onchain identity and reputation is a core piece of Chainchat, as it interfaces directly with many of Zapper’s discovery and account profiling features. Your chainchat identity is  fundamentally onchain, unlike Twitter or Telegram.

# Future Plans
Considering the term "guilds" over "channels" is on the table, as perhaps “guilds” conveys more accurately its concept. 

As channels mature and grow, they will unlock different features. This feature is akin to Discord's server boosting. Some of them may include:
- Moderator assignments
- Thread creation
- Member-specific reply blocking
- Custom Emojis

Boosts can be member-specific or channel-specific.

Section still in construction - awaiting community feedback.
