# Lars
A vehicle store about EVs! I forgot to add license sorry.

# DEVELOPER NOTE (READ THIS)
LARS is intended to be a modern, fast, and scalable platform centered around electric vehicles, simulation content, and interactive automotive experiences. The site should feel clean, responsive, and highly optimized across all devices, especially mobile and low-power machines. Performance is not optional — it is a core feature.

The design philosophy should stay minimal but futuristic. Avoid clutter, unnecessary animations, or heavy assets that slow down loading. If animations are used, they must be GPU-accelerated and optional to disable in settings. The interface should prioritize clarity, speed, and smooth interaction over visual complexity.

All pages should follow a consistent layout system. Navigation must remain predictable and accessible at all times. No hidden menus that confuse users. The header should remain lightweight and include only essential navigation links. Footer content should include legal information, versioning, and update logs where applicable.

The EV content system should be modular. Each vehicle or EV entry must be stored in a structured format (JSON or equivalent) so it can be dynamically rendered on the frontend. Hardcoding vehicle data into HTML files is not allowed unless absolutely necessary for prototypes. Future expansion must be considered at all times.

Search functionality must be fast and tolerant of user input errors. It should support partial matching, keyword correction, and category filtering (e.g., SUV, truck, performance EV, concept vehicles). Results should load instantly or near-instantly without full page reloads.

Any interactive features (such as vehicle comparison tools, simulation previews, or animation demos) must degrade gracefully. If a browser cannot handle advanced features, the user should still be able to view core content without errors or broken layouts.

Security is mandatory. No user input should be trusted without validation. Even if the site does not currently include accounts or authentication, the architecture should assume future expansion into user profiles, saved vehicles, or personalization features.

Code structure must remain clean and modular. Separate concerns clearly: UI components, data handling, utilities, and configuration should never be mixed. Avoid duplicated logic. Reusable components should be preferred over copy-paste implementations.

All assets (images, models, audio if used) must be optimized. Large files should be compressed or lazy-loaded. The site should never block rendering due to unoptimized media.

Future roadmap consideration: the system should be prepared for integration with AI-driven features, including vehicle recommendation systems, natural language search, and interactive EV comparisons.

Finally, every change pushed to production must be reviewed for performance impact, readability, and compatibility. No experimental feature should be deployed without fallback behavior.
© 2026 Lars, All rights reserved.
