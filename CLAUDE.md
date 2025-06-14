# ADHD App Development Notes

## Project Overview
This is an ADHD support application designed to help users manage tasks, improve focus, and build positive habits.

## Key Features
- Task management optimized for ADHD users
- Flexible reminder and notification system
- Focus timer with Pomodoro technique
- Habit tracking and analytics
- ADHD-friendly UI design
- Offline support with data sync

## Development Environment
Using Haconiwa for multi-agent development with 4 teams:
1. Frontend Team: UI/UX implementation
2. Backend Team: API and data management
3. Support Features Team: ADHD-specific features
4. UX/Accessibility Team: User experience optimization

## Commands
```bash
# Start development environment
haconiwa apply -f adhd-app-haconiwa.yaml

# Connect to development session
haconiwa space attach -c adhd-app-company -r room-01

# Run tests
npm test

# Build project
npm run build
```

## Important Notes
- Focus on accessibility and ADHD-friendly design patterns
- Keep UI simple and distraction-free
- Implement progressive disclosure for complex features
- Use clear visual feedback and progress indicators