# Foster Match

A matching tool for small animal rescues. Pick an animal that needs a foster home and see which homes fit, ranked, with the reasons shown.

**Live demo:** https://rosebrown802.github.io/foster-match/

All animals, people and the rescue in the demo are fictional sample data.

## The problem

Small rescues place animals by memory and group text. A coordinator has to remember which foster has a spare room, who can bottle-feed, whose dog won't tolerate cats, and who is already full. When four bottle babies arrive at 9 p.m., that takes time the kittens don't have.

## What it does

- **Rules out homes that can't work**, and says why: wrong species, no room, resident pets or young children the animal can't live with, no bottle-feeding experience, medical needs beyond the home's setup, no separate room, or a stay longer than the home can commit to.
- **Ranks the homes that are left** on a 100-point scale, using age-group preference, experience, daytime availability for feedings, comfort with shy animals, medical skill and distance.
- **Flags what to check first.** Anything that lowered a score is listed, so the coordinator makes the final call.
- **Lets you add a foster home** and see where it ranks right away.

The matching rules are written out in plain language on the How it works tab.

## How it was built

I foster cats for a Vermont rescue, and the rules come from that experience. I designed the product, the matching rules and the interface, and built it with Claude as my coding partner. It is a single HTML file with no dependencies and no server, so any rescue can open it and try it.

## What a real version would add

- Sign-in for coordinators, and a form fosters fill in themselves
- Saved placements, so each home's open space updates on its own
- A text or email to the top three homes when an urgent animal comes in

## About

Built by Rose A. Brown, creative director and writer. [Portfolio](https://rosebwn.com) · [LinkedIn](https://linkedin.com/in/rosebwn)
