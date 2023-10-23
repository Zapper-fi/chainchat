<img width="637" alt="image" src="https://github.com/Zapper-fi/chainchat/assets/6855274/1fd3e189-f59c-4575-8fb1-3b4e1295936c">

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
