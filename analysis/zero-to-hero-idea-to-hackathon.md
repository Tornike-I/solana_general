# Analysis: "Zero to Hero: From Idea to Hackathon" (SolanaCZE)

- **Video:** https://www.youtube.com/watch?v=JD8ZwgW6ydc
- **Speaker:** Sven Welsch (SolanaCZE community, works at Accretion)
- **Recorded:** 2026-09-16, FIT VUT Brno (Studentská unie)
- **Length:** 74:44 (the first ~6 min is music only, so the talk starts at ~6:00)
- **Format:** casual beer meetup, the first Solana event in Brno, about 10 people in the room

> Based on YouTube's English auto-captions plus frames pulled from the video, so quotes may have small caption errors.

## Structure

| Time | Segment |
|---|---|
| 0:00–6:00 | Music, nothing happening |
| 6:00–10:00 | Intro and the **Colosseum hackathon**: the biggest Solana hackathon, held twice a year. It's multi-chain for the first time, about 5,000 competitors, and at least 10 teams get **$250k startup funding** |
| 12:00–16:00 | Who SolanaCZE is: meetups twice a month, weekly co-working, and a goal to become an official Superteam. Past Prague build-station projects: Cushion (CTU students) and Segment AI (which demoed at a summit in Belgrade) |
| 16:00–20:00 | **The Build Station pitch** (details below) |
| 20:00–26:00 | Web3 basics for beginners (you actually own your stuff), use cases (payments, consumer apps, DeFi, DePIN, AI), why Solana (fast, good UX, strong community) |
| 26:00–30:00 | Audience introductions: mostly BUT and Masaryk cybersecurity/IT students, a few working devs |
| 30:00–36:00 | **How to build a hackathon MVP** (the most useful part) |
| 36:00–74:00 | Pitch contest: 1-minute Web3 ideas, with 3 × 50 USDC prizes |

## SolanaCZE Build Station

- **Oct 3–7, 2026, Marina Pivovar, Prague** (buildstation.cz). It's 5 days of co-working, Saturday to Wednesday, powered by Superteam.
- Free food and drinks, mentors, technical, UX/go-to-market and security feedback, team matching.
- Prizes: a **$10k pool**, a **$3k Marinade side track** (Solana staking) and a **$500 Accretion side track** (research/security).
- **Demo day is Wed Oct 7**, with pitches in front of 2–3 VCs. They offered to cover travel for people who can only come to demo day.
- Projects must also be submitted to Colosseum.
- Goal: "Help teams submit stronger projects to Colosseum."

## The core advice: from idea to MVP (slide at ~31:40)

**Don't start with a huge protocol.** You need six things: a clear problem, a specific user, one core action, a working prototype, a simple demo and a clear story.

| A good hackathon MVP has | A bad one has |
|---|---|
| One real user flow | A 30-page whitepaper |
| One working transaction | No working product |
| One clear problem | "AI + blockchain" with no user |
| One reason why Solana helps | Too much infrastructure |

Other points he made:

- Several past winners wrote **no on-chain code**. They combined existing integrations (payments, NFTs, DeFi APIs) with better UX.
- Only build infrastructure if you're a genius. Otherwise, build for normal people.
- Use AI heavily: Claude or GPT can get you in two days what used to take months.
- Teams of 2–3 work best.
- An audience tip: **Colosseum has a public MCP server**. Plug it into Claude to check whether your idea has already been built. An existing project doesn't rule the idea out; it may just not have been built well yet.
- solana.com has a page of old ideas that were good but didn't succeed, worth revisiting.

## Ideas pitched, and what the room said

1. **A better Solana program tester/debugger** (an improved "Better Call Sol"), with saved and shareable transaction templates. Sven agreed it makes sense. This was the strongest dev-tool idea.
2. **Matching flatmates and apartments in Brno.** The Web3 angle came out in discussion: on-chain tenant reputation, plus putting the deposit in DeFi so it visibly earns interest.
3. **A universal Solana feedback platform**, with feedback ranked by signing with a wallet that holds capital, an anonymous option and LLM summaries for developers. Sven liked it because even auditors struggle to reach protocol teams.
4. **A quest platform with strong proof-of-humanity**, because quest farmers kill these platforms. The point was that better identity tech now makes older ideas worth revisiting.
5. **Stake-to-touch-grass**: you set a goal, an AI checks your photo, and people who miss lose their stake to the pool. The room's critique was anti-cheat: AI images are hard to detect, which is why GPS step counters win. The suggested fix was peer verification plus reputation.
6. **Investing in amateur UFC fighters.** The room pushed back with "why Solana?" Suggested reframes were funding a fighter's training, or an NFT as early-backer proof, similar to poker stake-backing.
7. **Ad spaces with a QR scan-to-earn reward**, and a variant that auctions stadium cube screen time. Concerns were measuring views, wallet friction, and trolls buying the screen.

## Takeaways

- The talk itself is thin. The useful material is the MVP slide, the "no on-chain code needed" point, and the Colosseum MCP tip. The pitch section is a good live demo of the "why do you need Web3?" test that most ideas failed.
- The ideas that held up all had a **natural on-chain reason**: reputation, transparent escrowed funds, stake/slash incentives, or wallet-signed proofs. Ideas where Solana was just bolted on got challenged.
- **Before building:** commit to one problem, one user flow and one transaction.
