# The Cookie Factory Workshop

  - Author: Sebastien Mosser ([mosser@i3s.unice.fr](mosser@i3s.unice.fr))
  - Reviewers: Philippe Collet, Quentin Cornevin, Etienne Strobbe
  - Version: 1.0 (Jan 16)
  - Duration: 3h 15' (including a 10' break)

## Motivations & Objectives

The goal of this workshop is to experiment story-driven development, on a real life case study. It is defined as an extension of the _Elephant Carpaccio_'s workshop designed by Alistair Cockburn. When experimenting the _Carpaccio_ with CS students, the main drawback is the artificiality of the case study, and the shortness of the iterations. It is well suited for experimented engineers, but does not suit students as well.

We decided to extend this workshop to address these issues. The idea here is to create a 3 hours session that will support concrete software development using thin stories in its backlogs. It also allows one to discuss about _(i)_ the importance of discussing with the client and _(ii)_ the notion of technical debt in a software product.

## Requirements

### Audience

  - Audience should be aware of object-oriented software development to understand the initial code given during the kickoff. 
  - Being familiar with the agile mindset  (_e.g._, the idea of continuously delivering value to a customer) is mandatory.
  - Having used stories in a previous project is a plus, but not mandatory. However, knowing the notion of story is mandatory. 
  - Team should be composed by 3 to 4 peoples.


### Material

  - The ratio of animator / teams should be one animator for 4 teams at most.
  - Print as many "Product Description Card" as participants (at least 2 per team)
  - Print a lot of "Story Card"s for backlog descriptions (up to twenty per team)
  - Print one "Backlog Template" per team (A3 sheet).
  - Print one "Product Owner" persona per team.

## Workshop Planning

<html>
<div align="center">
  <table>
    <tr><th>Step</th><th>Time box</th><th>Total time</th></tr>
    <tr><td>Product Kickoff meeting</td><td>20'</td><td>20'</td></tr>
    <tr><td>Product backlog design</td><td>25'</td><td>45'</td></tr>
    <tr><td>Break</td><td>10'</td><td>55'</td></tr>
    <tr><td>Backlog design debriefing</td><td>10'</td><td>65'</td></tr>
    <tr><td>Product development iteration #1</td><td>25'</td><td>90'</td></tr>
    <tr><td>Product status meeting #1</td><td>10'</td><td>100'</td></tr>
    <tr><td>Iterations #2 &amp; #3</td><td>70'</td><td>170'</td></tr>
    <tr><td>Final debrief</td><td>25'</td><td>195'</td></tr>
  </table>
</div>
</html>

## Workshop Description

### Product kickoff meeting (20 minutes)

The animator describes the product we are going to build together, that is, the _Cookie on Demand_ (CoD) system. The client who ordered this product is _The Cookie Factory_ (TCF), a bakery brand with shops in all major town of the US. CoD is an innovative system that allows a customer to book cookies online (pre-made recipes or customized ones), select a _TCF_ bakery and an hour for pick-up. Cookies are prepared _on demand_, ensuring warm cookies for happy customers. A proof of concept was originally implemented. 

This kickoff meeting describes this very product, and the initial stories that were implemented as part of the proof of concept.

**Note for animators**: 

  - Insist heavily on the fact that you are representing the client in this workshop. 
  - Distribute Product description cards to the teams.

### Iteration #0: Product Backlog Design (25 minutes)

The goal of this iteration is to produce _(i)_ the initial product backlog, and _(ii)_ the backlog for the first product development iteration. Each product development iteration will last 25 minutes.

Each story is written down on a _Story Card_. Backlogs are implemented as piles of story cards.

**Note for animators**:

  - Ensure that the backlogs are properly produced in an organized way: cards must be syntactically correct (all fields filled), and organized into piles.
  - Do not discuss with the teams as client representative if not invited to.
  - Emphasize during the session that the product backlog is not definitive and will evolve during the workshop if necessary.
  - Encourage teams to fill the backlog with stories
  - Check that the stories  are _(i)_ thin enough to fit in a 25 minutes time box and _(ii)_ in sufficient quantities for the upcoming iterations
  
### Team Break (10 minutes)

Get the teams out of the room for the next 10 minutes.

**Note for animators**:

  - During the break, validate the backlog defined for the next iteration. 
  - Reject all stories that does not fit client expectations or that has low value with respect to others not present in the sprint.
  - Give a written feedback (a few words) on the story card when a story is rejected

### Backlog Debriefing (10 minutes)

Get the team back in the room. 

**Note for animators**:

  - Debrief what happened during the break. 
  - Explain globally why stories were rejected during the break
  - Emphasize the importance of discussing with client representative!
  - Each Team nominates a _Product Owner_, in charge of maintaining the backlogs consistent and exchanging with the client.

### Product Development Iteration #1 (25 minutes)

Start the first product development iteration. Teams work on the product development, implementing stories as defined in the backlog. The backlog is groomed by the PO, who exchanges with animators to identify value, ordering of stories, keep the count of implemented stories, ... 

Each two implemented stories, the team summons a demo with a client representative to validate the development. A story is _done_ when validated by the client representative.

At the end of the iteration, an iteration backlog is available for the upcoming one.

**Note for animators**:

  - Be pithy (_aka_ short and sharp) in your feedback, as many teams are around.
  - When not in a demo or discussing with a PO, look at the backlogs and ensure that it is properly groomed by the PO. 

### Product status meeting #1 (10 minutes)

I a few sentence, each team describes to the others:

  1. What was planned for this iteration;
  2. What happened during this iteration;
  3. What is planned for the next one.

**Note for animators**:

  - Ensure that the teams are efficient during this session, use a stopwatch and cut them when time's up.
  - Be sure that everybody listen to everybody.

### Iteration #2 & 3 (70 minutes)

  - Repeat two times:
    - Product development iteration: 25 minutes
    - Product Status Meeting: 10 minutes.

**Note for animators**:

  - Like the first one, ensure that the stories are validated two per two with a client representative
  - Check the backlog status with the PO when asked for.

### Final Debriefing (25 minutes)

Exchange with the teams about what happened in this workshop. 

**Note for animators**:

  - Use a ball to model speech and throw the ball from one team to another one.
  - Discussion leads:
    - Was it _that_ easy to develop the CoD system?
    - What was the role of the client in the software development process?
    - What were your biggest mistakes in this workshop? Biggest achievements?
    - How can you apply this workshop to your very projects?
    - Technical debt: Were the initial choices relevant at the end? Were they initially relevant?
