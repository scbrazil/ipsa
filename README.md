# ipsa

**Author: [Sean Brazil](https://github.com/scbrazil)

Ipsa scans inputted software/app Terms of Service and provides general, understandable information about its terms in layman's terms.

As technological capabilities increase, so too does the concern over privacy, protection, and legal rights. Despite this, agreeing to new software use agreements typically happens without a second thought. This is not because we don't care. It's often because (1) we don't understand the terms, and (2) we don't feel like we have a choice.

Ipsa breaks legalese down. Users submit plain text (just copy and paste) into Ipsa, which scans for important legal concepts. After scanning, this information is available by single clicks, so users can learn as they read.

Ipsa offers simple metrics regarding the presence of legal concepts in agreements. While this is not a grade of the overall agreement, it assesses the presence of a keyword or clause generally to display whether it could (1) favor the licensee or the licensor, (2) is neutral or restrictive to either party, and (3) is common or rare in software license agrements.

Ipsa is built with React (using Hooks) and Express. Content is stored in a MongoDB database built and seeded with Mongoose. Previously submitted Terms of Service/Terms of Use/Terms & Conditions are not stored, making Ipsa dynamic and responsive to each submission.

Ipsa exists for educational purposes. Neither Ipsa nor its author(s) can offer legal guidance or instruction. Ipsa exists solely to promote the understanding of ubiquitous legal terms and concepts. Ipsa cannot discern the overall qualities or effects of any Terms or Contract. While Ipsa serves to make concepts and keywords understandable, the overall effects of any contract depend upon its sum as much as its parts. Users should seek legal counsel for guidance prior to committing to any legally binding agreement.



Future additions:
1. PDF scanning.
2.