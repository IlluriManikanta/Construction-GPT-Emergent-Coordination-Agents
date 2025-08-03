# Construction-Agent README
AI Multi-Agent Competition at the UC Berkeley Agentic AI Summit, sponsored by Schmidt Sciences

We are a team of three: Haonan Zhu, Manikanta Illuri, and Yuexing Hao. On August 2nd, 2025, we developed a multi-agent simulation titled ConstructionAgent as part of the SSCI Multi-Agent Challenge at the UC Berkeley Agentic AI Summit.

📣 Our project was awarded 1st place in our competition track, recognized for its demonstration of emergent communication, coordination under constraint, and agent-driven problem solving.

ConstructionAgent models a system in which four language model-based agents work together to achieve a shared objective: building a townhouse. Each agent is assigned a distinct construction-related task—such as architectural design, structural engineering, landscaping, or instruction documentation. To complete their task, each agent must gather a specific set of tools and resources. However, at the beginning of the simulation, resources are randomly distributed among all four agents, and no agent starts with all the tools they need.

The agents communicate through turn-based natural language conversation, reasoning about their own needs and those of others based on limited information. They must request, offer, and trade resources strategically in order to fulfill their task-specific goals. Importantly, there is no pre-programmed communication protocol or language format. All coordination must emerge dynamically, requiring agents to invent shorthand, build shared understanding, and adapt to each other’s communication styles.

Once an agent collects all of the tools required for its task, it declares itself “Equipped for [task].” When all four agents have declared they are equipped, the group signals overall completion by outputting “Ready to build.” The simulation then ends automatically.



💡 Why This Project Matters

This project demonstrates how large language models can be deployed as autonomous agents to coordinate, negotiate, and solve problems in decentralized, information-asymmetric environments. Through this work, we gained valuable insights into the emergence of structured language, the importance of adaptability in agent interaction, and the potential of LLMs in simulation-driven collaboration. It also raised fascinating questions about how pragmatic language use and reasoning can emerge purely from task pressure and environmental structure—without explicit instructions or schemas.

We believe this line of exploration is increasingly relevant as real-world multi-agent systems become more common across fields like robotics, digital assistants, and distributed AI infrastructure.

![Construction GPT Logo](construction_GPT.png)

