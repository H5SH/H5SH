```TypeScript
// Hasham Asad – Full Stack Dev | Game Dev | AI Enthusiast

type TechStack = {
  languages: ['JavaScript', 'TypeScript', 'Python', 'Kotlin', 'Dart', 'PHP', 'Lua'];
  frameworks: ['React', 'Next.js', 'Flutter', 'Laravel', 'Jetpack Compose', 'Love2D'];
  tools: ['Firebase', 'Supabase', 'PostgreSQL', 'FastAPI', 'YOLOv8', 'Agora', 'GraphQL'];
};

type Project = {
  title: string;
  description: string;
  tech: string[];
  links: { live?: string; repo: string };
};

const featuredProjects: Project[] = [
  {
    title: 'Procedural Mario Game',
    description: 'Procedurally generated platformer with random keys, enemies, and level scaling.',
    tech: ['Lua', 'Love2D', 'Procedural Gen'],
    links: {
      live: 'https://hasham-projects.vercel.app/',
      repo: 'https://github.com/H5SH/CS50G-Mario-Project4',
    },
  },
  {
    title: 'Zelda-style Dungeon Adventure',
    description: 'Top-down action game with sword mechanics, dungeon gen, and power-ups.',
    tech: ['Lua', 'Love2D', 'Event System'],
    links: {
      live: 'https://hasham-projects.vercel.app/',
      repo: 'https://github.com/H5SH/CS50G-Zelda-Project5',
    },
  },
  {
    title: 'Masked Input Field (Flutter Package)',
    description: 'Customizable masked input with focus handling and input masks.',
    tech: ['Flutter', 'Dart'],
    links: {
      live: 'https://pub.dev/packages/masked_boxed_field',
      repo: 'https://github.com/H5SH/masked-boxed-field',
    },
  },
  {
    title: 'AI Contact Center Tester (PathSim)',
    description: 'Automated testing platform using LLMs and voice interaction APIs.',
    tech: ['FastAPI', 'YOLOv8', 'Retell AI', 'Vogent'],
    links: {
      repo: 'Private/Client Repo',
    },
  },
];

const contact: Record<'email' | 'portfolio' | 'github', string> = {
  email: 'hasham.asad.b@gmail.com',
  portfolio: 'https://hasham-projects.vercel.app/',
  github: 'https://github.com/H5SH',
};

// 👋 Hi, I’m Hasham
console.log(`
  Full-Stack Developer | Game Dev | AI Explorer

  • Built 10+ games (Flappy, Breakout, Match-3, Mario, Zelda)
  • Cross-platform apps with Flutter, React Native, Kotlin
  • Real-time chat, video calls, smart inputs, and more
  • YOLOv8 AI models for smoke, wire, and contact center testing

  Let’s build cool stuff together!
`);
```
