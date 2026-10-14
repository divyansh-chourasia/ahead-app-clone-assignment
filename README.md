# Ahead app clone

A one-page Next.js copy of the Ahead marketing site. One running copy is at https://ahead-app-clone.netlify.app/.

`app/page.js` stacks the sections. The bar stays at the top. Emotions, Manifesto, Self-awareness test, and Work With Us jump to `#banner1`, `#banner2`, `#banner3`, and `#banner4`. Download leaves this site. The footer shows the logo, the word ahead, AugustsraBe 26, 10117 Berlin, hi@ahead-app.com, an App Store image, and a 2023 copyright line.

The first band is violet. It says "Master your life by mastering emotions", credits Divyansh Chourasia, and shows an App Store image with the line "100+ App Store reviews". The stars are Font Awesome classes, and the page does not load that stylesheet. The banner image spins in once. Under it: "EQ beats IQ", then a row of the same card, "You argue with a colleague", repeated across the row.

The orange band says "Built out of frustation" and "Meet the ahead app", with a short description of a pocket coach. The flower and leaf images use the class `infinite-rotation`. Then "Self-improvement. Ugh" and a short list, then "Be the best you with EQ".

The blue band asks "Ever wondered what others think of you?" and describes three steps: answer questions, let others answer the same ones, compare the two. Under that, "Before you get started" quotes a privacy line, shows a signature image, and a Start a test button that leaves this site. The line under the button says "Take only 5 minutes".

The indigo band is "Work With Us", with an About blurb and a Product blurb, then four placeholder cards. "Open Vacannies" is three copies of Senior Full-Stack Engineer: full time, Berlin or remote, $65k-85k. Apply Now appears on hover and has no destination.

`framer-motion` fades and slides most of these blocks when they scroll into view.

## Run

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000). `npm run build` writes the production build, and `npm start` serves it.

`app/layout.js` loads Inter through [`next/font`](https://nextjs.org/docs/basic-features/font-optimization).

This project was bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app). The references from that README:

- [Next.js](https://nextjs.org/)
- [Next.js documentation](https://nextjs.org/docs)
- [Learn Next.js](https://nextjs.org/learn)
- [Next.js on GitHub](https://github.com/vercel/next.js/)
- [Deploy on Vercel](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme)
- [Next.js deployment](https://nextjs.org/docs/deployment)
