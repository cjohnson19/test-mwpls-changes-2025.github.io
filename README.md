<style>
#program-table {
  text-align: left;
  padding: 5pt;
  border: none;
}
.session-table {
  padding:0pt;
  border:none;
}

#program-table tr td, .session-table tr td {
  border: none;
  padding: 5pt;
}

.session-table p {
  margin-bottom: 2px;
}

.session-table p:nth-child(1) {
  font-style: italic;
  pointer-events: none;
}

.session-table p:nth-child(2)::after {
  content: " (Abstract)";
  font-style: normal;
  pointer-events: auto;
  color: grey;
}

.session-table p:nth-child(2) {
  margin-left: 10px;
}

#program-table tr td:nth-child(2) {
  width: 100%;
}
#program-table tr td, .session-table tr td {
  vertical-align: top;
}
</style>
<center>
<h1>2025 Midwest Programming Languages Summit</h1>
</center>

The 2025 Midwest Programming Languages Summit will take place on
<i>Saturday, December 13, 2025</i>, hosted by the [*Department of
Computer Science and Engineering*](https:cs.umn.edu)  at the
[*University of Minnesota, Twin Cities*](https://umn.edu).

The [*Midwest Programming Languages Summit*](https://mwpls.org) is an
informal workshop that is intended to foster the exchange of ideas and
to promote collaboration among faculty and students in the Greater
Midwest area. Anyone interested in programming languages and compilers
— including applications to areas such as systems, software
engineering, and human-computer interaction — is invited to
attend. Our aim is to have a broad selection of talks and posters
about ongoing research and any other topics that may be of interest to
the programming languages community. Student participation is
especially of interest; travel awards facilitated by a grant from the
National Science Foundation are available to encourage such
participation. The summit will have no formal proceedings, but
abstracts and slides will be distributed on the web after the
event.

This year's event is being organized by 
[Favonia](https://favonia.org/), 
[Gopalan Nadathur](https://cs.umn.edu/~ngopalan), and 
[Eric Van Wyk](https://cs.umn.edu/~evw)



# Dates

The important dates to keep in mind and deadlines to adhere to are the
following:


- **Friday, November 14, 2025:** Deadline for
  *[talk and poster proposals](https://forms.gle/wvwAzPzLdRsFEzKR7)*
  and to
  *[apply for travel grants](https://forms.gle/JrroCo1eexijSPJF8)*.
- **Wednesday, November 19, 2025:** Notification deadline for
talk/poster acceptance and grant awards
- **Monday, November 24, 2025:** Deadline to 
  *[register to attend](https://forms.gle/oKL5qQW4SiG2vaAA7)*.
- **Saturday, December 13, 2025:** Meeting date.

# Program  

<table id="program-table">
  <tr>
    <td>8:00-9:00</td>
    <td>(3-176 Keller Hall) <b>Registration Breakfast</b></td>
  </tr>
  <tr>
    <td>9:00-9:00</td>
    <td>(3-180 Keller Hall) <b>Welcome and opening Remarks</b></td>
  </tr>
  <tr>
    <td>9:10-9:20</td>
    <td>
      (3-180 Keller Hall) <b>Some words from our corporate sponsors</b> (AWS, Galois, SIFT)
    </td>
  </tr>
  <tr>
    <td>10:20-10:50</td>
    <td>
      (3-180 Keller Hall) <b>Session 1 of contributed talks</b> (Chair: TBD)
      <table class="session-table">
        <tr>
          <td>9:20-9:35</td>
          <td>
            <p>Structural Information Flow: A Fresh Look at Types for Non-interference</p>
            <p>Hemant Gouni, Frank Pfenning, Jonathan Aldrich</p>
          </td>
        </tr>
        <tr>
          <td>9:35-9:50</td>
          <td>
            <p>A Flow-Sensitive Refinement Type System for Verifying eBPF Programs</p>
            <p>Ameer Hamza, Lucas Zavalía, Arie Gurfinkel, Jorge A. Navas, Grigory Fedyukovich</p>
          </td>
        </tr>
        <tr>
          <td>9:50-10:05</td>
          <td>
            <p>Gradual Environment Classifiers</p>
            <p>Tianyu Chen, Darshal Shetty, Jeremy G. Siek, Chao-Hong Chen, Weixi Ma, Arnaud Venet, Rocky Li</p>
          </td>
        </tr>
        <tr>
          <td>10:05-10:20</td>
          <td>
            <p>Ground stratified induction for the logic of definitions</p>
            <p>Nathan Guermond, Gopalan Nadathur</p>
          </td>
        </tr>
      </table>
    </td>
    <tr>
      <td>10:20-10:50</td>
      <td><b>Break</b> (refreshments provided outside to 3-180 Keller Hall)</td>
    </tr>
    <tr>
      <td>10:50-11:50</td>
      <td>
        (3-180 Keller Hall): <b>Session 2 of contributed talks</b> (Chair: TBD)
        <table class="session-table">
          <tr>
            <td>10:50-11:05</td>
            <td>
              <p>On the Relationship Between Environment Classifiers and Contextual Modal Types</p>
              <p>Tianyu Chen</p>
            </td>
          </tr>
          <tr>
            <td>11:05-11:20</td>
            <td>
              <p>Checking &delta;-Satisfiability of Reals with Integrals</p>
              <p>Cody Rivera, Bishnu Bhusal, Rohit Chadha, A. Prasad Sistla, Mahesh Viswanathan</p>
            </td>
          </tr>
          <tr>
            <td>11:20-11:35</td>
            <td>
              <p>A Relevance Sampler for μRustₛₗ</p>
              <p>Breandan Considine</p>
            </td>
          </tr>
        </table>
      </td>
    </tr>
  </tr>
</table>

<!--

The main venue for MWPLS 2025 is Keller Hall: Registration will take place in Room 3-176 Keller Hall and the talks will be held in Room 3-180 Keller Hall. Lunch and the poster session will take place in the Beacon Room of the Rec Center, which is about a block (or 5 minutes walking distance) east of Keller Hall.

The program for the summit is the following:

8:00 - 9:00 (3-176 Keller Hall): Registration and breakfast

9:00 - 9:10 (3-180 Keller Hall): Welcome and opening remarks 

9:10 - 9:20 (3-180 Keller Hall):  Some words from our corporate sponsors (AWS, Galois, SIFT)

9:20 - 10:20 (3-180 Keller Hall): Session 1 of contributed talks. Chair: TBD
9:20 - 9:35: Structural Information Flow: A Fresh Look at Types for Non-interference
Hemant Gouni, Frank Pfenning, Jonathan Aldrich (Abstract)

9:35 - 9:50: A Flow-Sensitive Refinement Type System for Verifying eBPF Programs
Ameer Hamza, Lucas Zavalía, Arie Gurfinkel, Jorge A. Navas, Grigory Fedyukovich (Abstract)

9:50 - 10:05: Gradual Environment Classifiers
Tianyu Chen, Darshal Shetty, Jeremy G. Siek, Chao-Hong Chen, Weixi Ma, Arnaud Venet, Rocky Li (Abstract)

10:05 - 10:20: Ground stratified induction for the logic of definitions
Nathan Guermond, Gopalan Nadathur (Abstract)

10:20 - 10:50: Break (refreshments provided outside to 3-180 Keller Hall)

10:50 - 11:50 (3-180 Keller Hall): Session 2 of contributed talks. Chair: TBD
10:50 - 11:05: On the Relationship Between Environment Classifiers and Contextual
                       Modal Types
Tianyu Chen (Abstract)

11:05 - 11:20: Checking δ-Satisfiability of Reals with Integrals
            Cody Rivera, Bishnu Bhusal, Rohit Chadha, A. Prasad Sistla, Mahesh 
Viswanathan

11:20 - 11:35: A Relevance Sampler for μRustₛₗ
Breandan Considine

11:35 - 11:50: Abella/Forum: A Framework for Reasoning about Linear Logic
 Specifications
Terrance Gray, Thomas Tector, Gopalan Nadathur

12:00 - 14:30: Lunch and Poster Session (Beacon Room, Rec Center)

The following posters will be presented in the poster session:

Colobus: AoS to SoA transformation of recursive tree-like ADTs
Vidush Singhal (Abstract)

Polygon: Symbolic Reasoning for SQL using Conflict-Driven Under-Approximation Search
Pinhan Zhao (Abstract)

Detecting Multi-Locale Anomalies in Chapel.
Raneem Abu-Yosef, Thomas Huddleston, Kirshanthan Sundararajah, Martin Kong (Abstract)


Towards Improved Subgoal Synthesis for Induction in SMT
Kartik Sabharwal, Andrew Reynolds, Cesare Tinelli (Abstract)

Towards Refinement Verification of Synchronous Programming with Automata 
Jiawei Chen, Serra Dane, Jean-Baptiste Jeannin (Abstract)

Automatic Certification of the Active Corner Method for Collision Avoidance
Nishant Kheterpal (Abstract)

Dependent-types for Python Libraries for Shape Analysis
Arnav Jain and Sankha Guria (Abstract)

Group Cohomology in Cubical Agda
Kelton OBrien (Abstract)

Biscotti: An Approach to Parallel Scheduling for Vectorized Encrypted Arithmetic Circuits
Vedant Paranjape, Aman Gupta, Sreevickrant Sreekanth, Dulani Wijayarathne, Raghav Malik, Milind Kulkarni (Abstract)


Ariadne: Discovering PBT Generator Weights with Dynamic Sampling
Francille Zhuang (Abstract)


Compiling Structured Operational Semantics to Executable OCaml Code
Linglong Meng (Abstract)

14:50 - 16:05 (3-180 Keller Hall): Session 3 of contributed talks. Chair: TBD
14:50 - 15:05: Virtualizing Continuations 
Cong Ma (Abstract)

15:05 - 15:20: System FD: Towards making ad-hoc polymorphism even less
ad-hoc
Apoorv Ingle (Abstract)

15:20 - 15:35: Code Style Sheets
Sam Cohen and Ravi Chugh (Abstract)

15:35 - 15:50: A Marriage of Scope Graphs and Reference Attribute Grammars
Luke Bessant (Abstract)

15:50 - 16:05: Flexible Efficient Memory Management and Compile-Time 
Specialization via Context 
Sam Estep and Joshua Sunshine (Abstract)

16:05 - 16:35: Break (refreshments provided outside to 3-180 Keller Hall)

16:35 - 17:35: (3-180 Keller Hall): Session 4 of contributed talks. Chair: TBD
16:35 - 16:50: Quantum Assertion Testing Without Mid-Circuit Measurement: Strategies
 and Lower Bounds
Shengyuan Yang and Charles Yuan (Abstract)

16:50 - 17:05: Safety Verification of Anytime Perception based Cyber-Physical Systems
Lipsy Gupta and Pavithra Prabhakar (Abstract)

17:05 - 17:20: Fluorite: A Calculus for SQL Queries With Ordering
Jesse C. Slater, Xinyu Wang, Ryan Marcus, Max S. New (Abstract)

17:20 - 17:35: Learning Short Clauses via Conditional Autarkies
Amar Shah, Twain Byrnes, Joseph Reeves, Marijn Heule (Abstract)

17:35 - 17:45: Closing remarks

18:15 - 20:30: Dinner
-->

# Event Details

## Venue

The workshop will be held in [Keller
Hall](https://campusmaps.umn.edu/kenneth-h-keller-hall), the home of
the Computer Science and Engineering Department on the east bank of the
Minneapolis campus of the University of Minnesota.

<center>
<iframe src="https://www.google.com/maps/d/u/0/embed?mid=1SD-pEHoj8tcwQb_7fbRYS6no-FEsTHk&ehbc=2E312F"
width="640" height="480"></iframe>
</center>

## Accommodation

The nearest hotel, which is only one block from Keller Hall is the [Graduate by Hilton
Hotel](https://www.hilton.com/en/hotels/mspgmgu-graduate-minneapolis/). Other
options that are all within walking distance include the [Days Hotel by
Winham](https://www.wyndhamhotels.com/days-inn/minneapolis-minnesota/days-inn-hotel-university-ave-se/overview?CID=LC:DI:20160927:RIO:Local:SM-diwnct)
on University Avenue, the [Hilton Garden
Inn](https://www.hilton.com/en/hotels/msputgi-hilton-garden-inn-minneapolis-university-area/),
and, just across the Mississippi river, the [Courtyard by
Marriott](https://www.marriott.com/en-us/hotels/mspdc-courtyard-minneapolis-downtown/overview/).

When considering other options, such as through Airbnb, it would be
prudent to check access by [public
transit](https://www.metrotransit.org/home) to the campus. The [Metro
Transit Green Line](https://www.metrotransit.org/route/green), for
example, has a stop right outside Keller Hall and it runs from
downtown Minneapolis (just a few stops away) all the way to downtown St. Paul
(many stops further away).

We will add more information about accommodation, such as about
special rates at hotels if we have been succeed in getting them. Be
sure therefore to check back here later in November. 


## Travel / Public Transit

### By air

One can fly to the [Minneapolis St. Paul International
Airport](https://www.mspairport.com/), code **MSP**.
From the airport, take the 
[Blue Line](https://www.metrotransit.org/route/blue) 
towards Minneapolis to the US Bank Stadium stop. From here, catch the
[Green Line](https://www.metrotransit.org/route/green)
towards St. Paul and get off at the East Bank stop. This is right in
front of Keller Hall where the workshop is taking place.

### By rail

Amtrak has a two connections between Minneapolis and Chicago that
makes for a pleasant journey arriving at the 
[Union Depot](https://www.uniondepot.org/) in St. Paul. The best
option may be the [Borealis](https://www.amtrak.com/borealis-train), a
dedicated line between Chicago and Minneapolis. The [Empire
Builder](https://www.amtrak.com/empire-builder-train), which goes via
St. Paul/Minneapolis from Chicago to Seattle and vice versa, is
another possibility. From the train station / Union Depot, take the
[Green Line](https://www.metrotransit.org/route/green)
towards Minneapolis and get off at the East Bank stop.


## Parking

Parking on the University of Minnesota East Bank campus is,
unfortunately, not the easiest of propositions. The best option for
day parking is to use University of Minnesota parking
ramps. Information on these facilities can be found in the
**University Parking** section of the [Keller
Hall](https://campusmaps.umn.edu/kenneth-h-keller-hall) web page. 



# Sponsors

The event is being supported by the [National Science
Foundation](https://nsf.gov), the [Department of Computer Science at
the University of Minnesota](https://cs.umn.edu), the automated
reasoning group in Minneapolis ([an internship program in automated
reasoning](https://amazon.jobs/en/jobs/3050073/2026-applied-science-internship-automated-reasoning-united-states-phd-student-science-recruiting))
of *Amazon Web Services*, the [Galois](https://galois.com) group in
Minneapolis and [SIFT: Smart Information Flow
  Technologies](https://sift.net). 


<table>
<tr>
<a href="https://nsf.gov"><img src="NSF.png" height="150" width="150"></a>
<img src="spacer.png" height="150" width="10">
<a href="https://cs.umn.edu"><img src="cse.png"
  height="100" width="813"></a>
  </tr>
<tr>
  <a
  href="https://amazon.jobs/en/jobs/3050073/2026-applied-science-internship-automated-reasoning-united-states-phd-student-science-recruiting"><img
  src="aws.png" height="150" width="293"></a>
  <img src="spacer.png" height="150" width="30">
  <a href="https://galois.com"><img src="galois.png" height="150" width="572"></a>
</tr>
<tr>
  <a href="https://sift.net"><img src="sift.png" height="150"></a>
  </tr>
</table>

