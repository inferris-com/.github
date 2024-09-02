# Welcome to Inferris! 🌟

Inferris is a unique community that seeks to forge meaningful connections through a vibrant Discord server, although we are working on a Minecraft network for any gamers out there. Our goal is to foster unity and nurture individuals so that everyone can thrive, both in fun and deep conversations. We won't be just a platform, but a sanctuary of love, compassion, and understanding—a haven for everyone to feel validated, understood, and accepted.

## Our vision
Inferris aspires to be a relaxed lounge where people can unwind, connect, and find help genuine meaning. We are building a community that reflects these values:

- **Compassion**: Emphasizing care and support for one another.
- **Connection**: Creating opportunities to forge real relationships and nurture a strong sense of belonging.
- **Unity**: Providing a safe, inclusive, and understanding environment.
- **Growth**: Encouraging self-discovery through discussions on life, challenges, and aspirations.

  ## What will you be able to do @ Inferris?
In the Inferris community, you will find a vibrant and welcoming space where genuine connection, unity, and meaningful conversations take center stage. Here are some of the key activities and experiences you can expect:

### 🌐 Discord Community
- **Icebreaker Games**: Break the ice through randomized pairings that help you connect with other members through thoughtful questions and casual conversation.
- **Trivia Clash Nights**: Team up with friends to test your knowledge across various trivia categories in a lively, competitive setting.
- **Movie Nights**: Unwind together with your fellow members while watching a selection of films across different genres, chatting and sharing thoughts as the night unfolds.
- **Collaborative Playlists**: Share music recommendations and discover new tunes with others through our collaborative playlists, bonding over common tastes.

### 🎮 Minecraft Network
- **Collaborative Projects**: Work together with others on large-scale builds and creative projects that strengthen bonds and bring members together.
- **Competitive Games**: Challenge yourself or your friends in fun, competitive games that focus on friendly rivalry and personal improvement.
- **Survival World**: Establish bases, form groups, and explore the limitless creativity of the survival world, where adventure meets collaboration.
- **Community Feedback**: Inferris is shaped by you! Share your ideas and concerns to help shape future gameplay, activities, and events.

### Under the Hood: Technical Features
Inferris boasts a large technology stack for many different reasons, which allows us to make what we are building in the first place.

**RESTful API Microservice:**

The REST API serves as the main point of entry for querying and updating player and server data, whether it's a request from a plugin, or from an external app.
- Built with Node.js and Express.js, and uses Redis and MySQL for the data layer.
- Allows custom software, such as an admin panel interface, to GET, POST, and PUT, and integrates with Redis PubSub to properly update the network to make local changes 
- Different endpoints

**Server Architecture:**
Our player data architecture, which uses the Inferris API, ensures seamless synchronization and accessibility across the network, using a carefully architected setup:
- Backend: BungeeCord and Spigot plugins form the foundation of the Minecraft-centered network, enabling smooth transitions between different game modes and servers.
- Caching: Caffeine caching stores frequently accessed data in memory during active sessions for rapid access. Redis provides an additional layer as a persistent in-memory data store, reducing latency and acting as a fallback for session continuity.
- Databases: MySQL offers robust, long-term storage of core player information like ranks, coins, and vanish state. Redis offers fast short-term caching solutions

**Verification System:**
Your identity is unified across the Inferris community via custom integrations:
- Minecraft-Discord Link: Link your Minecraft account to our Discord server, synchronizing in-game ranks and roles.
- XenForo Add-On: The Inferris forums use custom integrations that allow players to verify their accounts, ensuring consistent identification across the community.

## Resources
* Discord: https://dsc.gg/inferris
* Website: https://inferris.com/community
* Support: https://support.inferris.com

## Acknowledgments for Services and External Contributions
In recognition of the services used, and for the sake of common courtesy, I'd like to express my thanks to the following:

- The developers of the essential services we rely on, like NGINX, Django, Postfix, Dovecot, MySQL, Redis
- XenForo developers, including Chris D, Jeremy P, Kier, Mike, and Naz.
- OVH for their service as our provider, enabling me to host various services, such as web hosting, databases, email infrastructure, and our API.
- md_5, a legend in the field. Also a big thanks to the PaperMC team.
- Cloudflare for security.
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
