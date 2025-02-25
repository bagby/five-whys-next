# Five Whys

This is an experimental app which attempts to use the Five Whys Paradigm with AI to answer interesting questions. It is very much a Work in Progress™.

## The Five Whys Paradigm

The Five Whys is a problem-solving technique used to explore the cause-and-effect relationships underlying a particular problem. The primary goal of the technique is to determine the root cause of a defect or problem by repeating the question "Why?" five times. Each answer forms the basis of the next question. The "five" in the name derives from an anecdotal observation on the number of iterations typically required to resolve the problem.

### Steps to Perform the Five Whys

1. **Identify the Problem**: Clearly describe the problem you are facing.
2. **Ask Why**: Ask why the problem happens and write down the answer.
3. **Repeat**: If the answer you just provided doesn't identify the root cause of the problem, ask "Why?" again and write down that answer.
4. **Continue**: Repeat the process until the root cause of the problem is identified. This may take fewer or more than five times.

### Example

1. **Problem**: The car won't start.
2. **Why?** The battery is dead.
3. **Why?** The alternator is not functioning.
4. **Why?** The alternator belt has broken.
5. **Why?** The alternator belt was well beyond its useful service life and not replaced.
6. **Why?** The car was not maintained according to the recommended service schedule.

By following these steps, you can identify the root cause of a problem and take corrective actions to prevent it from recurring.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.
