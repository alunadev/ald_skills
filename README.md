# My curated List of skills for Antigravity and Claude Code

- [skill-creator](https://github.com/anthropics/skills/tree/main/skills/skill-creator) - Template/helper to build new Claude skills.

## References
- https://code.claude.com/docs/en/skills
- https://antigravity.google/docs/skills
- [Awesome Claude Skills by VoltAgent](https://github.com/VoltAgent/awesome-claude-skills)
- [Awesome Claude Skills by BehiSecc](https://github.com/BehiSecc/awesome-claude-skills/)
- [Agent Skills Marketplace](https://skillsmp.com)

## 📁 Repository Structure
```bash
ald-skills/
├── README.md
├── design/
│   ├── frontend-design/
│   ├── ui-ux-pro-max/
│   ├── web-design-guidelines/
│   ├── react-best-practices/
│   └── imagen/
├── development/
│   ├── skill-creator/
│   ├── ask-questions-if-underspecified/
│   └── varlock-env-management/
├── testing/
│   ├── test-driven-development/
│   ├── systematic-debugging/
│   ├── defense-in-depth/
│   ├── find-bugs/
│   ├── deslop/
│   └── code-review/
├── deployment/
│   └── vercel-deploy/
└── expo/
    ├── expo-app-design/
    ├── expo-deployment/
    └── upgrading-expo/
```

## 🎨 Design

- [**claude-code/plugins/frontend-design**](https://github.com/anthropics/claude-code/tree/main/plugins/frontend-design) - Design beautiful, accessible, and functional frontends
- [**ui-ux-pro-max**](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) - Advanced UI/UX design patterns and best practices
- [**vercel-labs/web-design-guidelines**](https://github.com/vercel-labs/agent-skills/tree/main/skills/web-design-guidelines) - Web design guidelines and standards
- [**vercel-labs/react-best-practices**](https://github.com/vercel-labs/agent-skills/tree/main/skills/react-best-practices) - React best practices and patterns
- [**sanjay3290/imagen**](https://github.com/sanjay3290/ai-skills/tree/main/skills/imagen) - Generate images using Google Gemini's API for UI mockups, icons, and visual assets

## 🛠 Development

- [**ask-questions-if-underspecified**](https://github.com/trailofbits/skills/blob/main/plugins/ask-questions-if-underspecified)- Prompt for clarification on ambiguous requirements
- [varlock-claude-skill](https://github.com/wrsmith108/varlock-claude-skill) - Secure environment variable management ensuring secrets never appear in Claude sessions, terminals, logs, or git commits.

## 🛡 Testing

- [test-driven-development](https://github.com/obra/superpowers/tree/main/skills/test-driven-development) - Write tests before implementing code: Use when implementing any feature or bugfix, before writing implementation code
- [systematic-debugging](https://github.com/obra/superpowers/blob/main/skills/systematic-debugging) - Use when encountering any bug, test failure, or unexpected behavior, before proposing fixes
- [defense-in-depth](https://github.com/obra/superpowers/blob/main/skills/defense-in-depth) - Implement multi-layered testing and security best practices.
- [**getsentry/find-bugs**](https://github.com/getsentry/skills/tree/main/plugins/sentry-skills/skills/find-bugs) - Find and identify bugs in code
- [**getsentry/deslop**](https://github.com/getsentry/skills/tree/main/plugins/sentry-skills/skills/deslop) - Clean up sloppy code
- [**getsentry/code-review**](https://github.com/getsentry/skills/tree/main/plugins/sentry-skills/skills/code-review) - Perform code reviews

## 🚀 Deployment

- [**vercel-labs/vercel-deploy-claimable**](https://github.com/vercel-labs/agent-skills/tree/main/skills/claude.ai/vercel-deploy-claimable) - Deploy projects to Vercel

## 📱 Expo Skills
Official AI agent skills from the Expo team for building, deploying, and debugging Expo apps.

- [**expo/expo-app-design**](https://github.com/expo/skills/tree/main/plugins/expo-app-design) - Design and build Expo applications
- [**expo/expo-deployment**](https://github.com/expo/skills/tree/main/plugins/expo-deployment) - Deploy Expo apps to production
- [**expo/upgrading-expo**](https://github.com/expo/skills/tree/main/plugins/upgrading-expo) - Upgrade Expo SDK versions

## 🔧 Installation

### Option 1: Clone and Symlink (Recommended)

```bash
# Clone this repository
git clone https://github.com/TU-USUARIO/my-antigravity-skills.git

# Create symlink to Antigravity skills directory
# On macOS/Linux:
ln -s $(pwd)/my-antigravity-skills/* ~/.gemini/antigravity/skills/

# On Windows (run as Administrator):
mklink /D "C:\Users\YOUR-USER\.gemini\antigravity\skills" "C:\path\to\my-antigravity-skills"
```

### Option 2: Manual Installation

```bash
# Clone this repository
git clone https://github.com/TU-USUARIO/my-antigravity-skills.git

# Copy skills to Antigravity directory
cp -r my-antigravity-skills/* ~/.gemini/antigravity/skills/
```

## 📝 Usage

Skills are automatically detected by Antigravity when placed in the skills directory. To use a skill:

1. Ensure the skill is in your `~/.gemini/antigravity/skills/` directory
2. Antigravity will automatically apply relevant skills based on context
3. You can also explicitly reference skills in your prompts

## 📬 Contact
If you want to contact me, you can reach me on [X](https://x.com/adrianlunadiaz).
