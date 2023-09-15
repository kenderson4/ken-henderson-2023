---
title: Org Design for Modern Software Dev Team
layout: post
post-image: "https://kenderson4.github.io/ken-henderson-2023/assets/images/people-are-the-focus.png"
description: There's a lot of theory out there as to how to build and structure a software development team. I'm sharing a view (the culmination of my experiences over the past 15 years) which I've recently had the opportunity to test.....and it worked really well! 
tags:
- Organization Design
- Software Development
- Operations
---

I've spent the last 10 years of my career building and leading teams, which has given me many opportunities to experiment with organizational design - trying to find the optimal design for the specific type of team/business.

I've played many different operations roles over my career, but in early 2020 I had the opportunity to join the software side of the business as the Head of Product Software Engineering. At the time there were 3-4 groups of developers located across 3 different geographies. 

## The Initial Challenges were...
- The established operating model did not afford personal development due to constant firefights.
- Line managers were being pushed so hard to deliver features that they didn't have the time to focus on individual Career Paths. So no one knew where they were going and lacked motivation and incentive.
- The lack of process and structure of team resulted in very little time to build meaningful features and too much churn/distractions.
- The technology of the product was aging - an 8 year old monolith of an application that was written in Java. The real challenge (related to the first bullet) is that no one was given time & encouragement to innovate. So development was slow & painful.
- Due to the above elements, the overall engagement score of the team was (not surprisingly) through the floor.
 
I was extremely fortunate to have a technically strong partner in this space ([Chris Williams](https://www.voodootikigod.com/)), so I didn't need to focus on the technical challenges. **My charter was to address the processes and scale the team by 2X in as short of time as possible.**

## Step 1 - Let's Organize
The very first thing I focused on was organization design - ensuring the structure was right and that we had the right people in the right roles. The initial design of the team was very hierarchical, where each group reported to a line manager and that line manager reported to me.

![Traditional Team Hierarchy](https://kenderson4.github.io/ken-henderson-2023/assets/images/traditional-hierarchy-example.png)

When it comes to organization design, there's a dizzying amount of resources out there. Instead of blindly adopting a structure, I took a step back and talked with every line manager and team member individually. It became very clear to me that we had awesome team with a eff-ton of potential, but line managers weren't given the time and remit to curate their teams, as they had to worry about;
- Building & running sprints - handling ceremonies and ad-hoc spikes
- Helping individual team members overcome technical issues
- Coordinating with Product Managers to ensure the engineering roadmaps were solid
- Career Paths for their individual team members
- Personal development for individual team members
- Interviewing - which was getting ready to increase as we needed to double the size of the team

On top of all that, this happened to be right at the beginning of Covid19. So the needs of the individual team members were high. Many team members were trying to figure out how to work from home - creating ad-hoc spaces with limited equipment. Emotions were high, as everyone had family, friends, and team members getting sick. So the need for line managers to simply spend time talking with people, and maintain a solid connection with their people was at an all-time high....yet none of them had the time to spend.

>*That's when it hit me - I need to create a structure that breaks up the responsibility of the line managers, giving specific focus to the product/sprint and specific focus to the people.* 

In years previous to that timeframe I had done a good amount of organization design for professional services teams within companies that had multiple business lines and within multiple regions, and had grown to appreciate a matrixed organizational structure. And of course who can forget the Spotify Squad/Tribe/Chapter/Guild model, which although highly talked about, it was interesting to hear that it was [never really put to use](https://www.jeremiahlee.com/posts/failed-squad-goals/).

So we (at this point I needed to bring the line managers on the journey along with me) decided on a mix of a couple of elements from a matrix model and the spotify model.

![Our New Model](https://kenderson4.github.io/ken-henderson-2023/assets/images/matrixed-software-team-example.png)

## Core Tenants of the New Model
- **Communities:** Groups of people with a common passion, led by a "Community Leader". e.g. people with the data community enjoy data-based challenges and staying in lock-step with the latest data frameworks and technologies. A critical point here - these **are not** silos that pin people to only work on a specific type of work. It was unanimous across the team that people wanted the ability to continue working across the entire stack, but having a "community of like-minded people (who worked across multiple workstreams) was key in ensuring consistency within the various disciplines within the team. So community members didn't have to pick-up specific types of tickets, but their insights were incredibly valuable when grooming those tickets with the team, as each community started establishing best-practices and standardized on technologies
- **Workstreams:** These were product focused groups led by a "Product Architect", and so that everyone could be in meetings together they were somewhat grouped by geography.
- **Product Architects:** They have No line management responsibilities. Rather they stay focused on gluing the team to the product manager. They build and run sprints, help team members overcome technical hurdles, and have an overall responsibility for the health and velocity of the "workstream".
- **Community Managers:** They have the line management responsibilities for individual team members, ensuring they have everything they need to be successful, from the necessary remote office set-up to a solid understanding of their career path. Over time Community Managers worked with their teams to set consistent standards and build roadmaps that represented the trajectory of the community. 

## Keys to Success
- **It's All About The People:** If executed well, the individual team members have 2 points of support and mentorship - a Product Architect that drives their day-to-day work and a Community manager that's supporting their growth and career path.
- **Communication:** With the above in mind, it's absolutely critical that Product Architects and Community Managers stay in lock-step. Otherwise they run the risk of creating a scenario where the individual team member gets pulled in 2 different directions....and the benefits of the matrix break down.
- **Community Manager Role is a Player/Coach Role:** A key element here is that the Community Manager role is designed to be a player/coach role, generally spending 50% or greater of their time with their hands on the technology. Which is a welcome aspect of the role by all of the community managers, as it enables them to keep their skills sharp and get a front-row look at the performance of their people and any challenges that they may be experiencing.
- **Individual Challenges:** If a team member is struggling with a specific task, or is just in a rough patch of life, the Product Architect is likely going to be the first one to observe these struggles. The beauty of this org design is they can lift the observations up to the Community Manager and not have to take their eyes to far off of the product/workstream. The Community Manager (being 50/50 player/coach) has the ability to dedicate a portion of their time to come alongside the individual team member.
- **Community Roadmaps:** After the first month or so of gelling, the communities starting coming up with their own strategic roadmaps, which was fantastic to see, but the without getting those elements sown into the *product* roadmaps, none of them would get executed. This is where the rubber hits the road on the relationship between the Product Architect and the Community Manager. The Community Manager needed to demonstrate the value of the elements on the *community* roadmap and influence the Product Architects to inject those into the *product* roadmap in the right places. Therein lies the ultimate synergy between product and community!
- **Matrix Guardian:** Full disclosure, I stole this terminology from Amy Kates & Jay R. Galbraith's [*Designing Your Organization: Using the STAR Model to Solve 5 Critical Design Challenges*](https://www.amazon.com/Designing-Your-Organization-Critical-Challenges/dp/0787994944), but it describes the role perfectly. You need someone who is constantly analyzing the intersections of the matrix and has the remit to course-correct where necessary. Do we have the right meetings and communication happening? Are individuals feeling supported? Is the output of the team quality and at-pace? Given that both the Product Architects and Community Managers reported to myself (Head of Software Engineering) I took this role on, and spent many hours analyzing the quality of interactions. I used 1-2-1 meetings as opportunities to sow the right seeds for those interactions and explore the root of some of the challenges. 
- **Scaling Up:** This structure enabled us to quickly spin-up (and down) new workstreams with the same best practices and consistent processes. Additionally, it allowed individuals to change workstreams **without changing line management**. The combination of those two elements meant that we could move very quickly when new needs arose.

Above is my experience and observations along the way. Feel free to reach out to me if you've got questions, thoughts, or just want to grab a beverage and chat!
