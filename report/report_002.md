## Applications of Software Visualization in modern Projects

When thinking about construction we find it natural to begin any project of reasonable size and complexity with a rough design. Afterwards the design iterates through multiple steps to refine it, check it's physical properties and how it fits into the scenery. Only then construction starts ideally realizing the project exactly as planned. These steps are known as a waterfall design approach. Most properties of a step have to be refined before continuing with the next one. In the early days of software engineering this was the exact approach used as well. Programmers spent more time  iterating their design on paper instead of typing code but other than buildings and bridges environment and expectations of software applications became more and more dynamic. In recent days most large scale projects have to be designed in record time while having to conform to longevity, reusability and an abundance of other criterions. Processes in the top companies are now agile and code has to be modular to reduce dependencies when switching components for the next weekly release. At some point the common visual aids became solely educational at least for programmers. Everything that keeps you from maximizing code output has to be reduced to a minimum. At this point frameworks rise and fall in a matter of months while the projects using them ideally live significantly longer. And within that the saying that the most permanent code is the one that was only to be a quick fix still holds it's truth.

One of the biggest struggles new hires of an established team have is understanding the existing code, working through mind numbing amounts of code in varying state of decay trying to add to the existing features without breaking them accidentally. Speaking from experience the old UML diagrams would come in handy right now. In many teams getting up to speed is a matter of months because the options are working through the existing code or consistently depend on others to integrate your code. With AI inching closer to write it's own projects only being restraint by it's memorisable context the second one becomes less and less viable. In construction the visual aids have mostly kept up with demand. It's time for software visualization to rise again. This report focuses on areas that could benefit from visualizations, what they could look like and how they improve existing workflows.

## Content

**1. Introduction**

- Brief overview of the importance of design in both construction and software engineering.
- Transition from the waterfall design approach to agile methodologies in software development.
- The necessity for modern software visualization tools.
- Outline of the report structure.

**2. Architecture**

- **2.1 Dependencies**
    - Explanation of software dependencies.
    - Challenges posed by complex dependency graphs.
    - Visualization techniques to manage and understand dependencies.
- **2.2 State of Modularization**
    - Importance of modular design in software development.
    - Methods to visualize and assess the modularity of a codebase.
    - Case studies or examples of successful modularization.

**3. Evolution**

- **3.1 Contributions**
    - Tracking and visualizing code contributions over time.
    - Tools for understanding the evolution of a codebase (e.g., version control visualization).
    - Importance of documenting changes and their rationale.
- **3.2 Code Decay and Refactoring**
    - Identifying areas of code decay.
    - Visualization techniques for code health and technical debt.
    - Strategies for effective refactoring to maintain code quality.

**4. Communication**

- **4.1 Who Works on What**
    - Importance of clear communication in software teams.
    - Tools to visualize team members' responsibilities and contributions.
    - Benefits of transparent workflows for team productivity and cohesion.
- **4.2 Estimating Story Points**
    - Role of story points in agile project management.
    - Visual aids to estimate and track story points.
    - Case studies of effective story point estimation and its impact on project success.

**5. Conclusion**

- Summary of key points discussed in the report.
- The current state and future of software visualization.
- Final thoughts on the importance of integrating effective visualization tools in software development processes.

## Architecture

In the evolution of projects most start as prototypes or additional features of existing projects that then grow to become their own. A prototype by definition is a project that aims to rapidly test new features in the least time possible. It achieves that at the cost of longevity and clear thought ought structure. Software prototypes tend to cut a lot of corners because they are designed to show results as quickly as possible. This is called technical debt. With time this technical debt hinders the developers to extent the product with new functionality because additional behaviour is prone to break the existing one due to unforeseen coupling.

At this point it's advisable to refactor the existing code to comply with generally accepted architectural principles. In most cases this means modularizing the code, implementing interfaces to further decuple the modules and spending some time to follow Liskov's Substitution Principle. In many cases developers stay under pressure to implement new features during this time as well putting the project in a continuous half refactored state. 

As a new developer in the team it's hard to follow these changes and developments in repositories with multiple thousands of lines of code because the mental graph of dependencies inside the code needs time and experience to build. Like any job it's expected to produce measurable output after some time forcing the new hire to seek help from more experienced co-workers or contributing blind and producing error prone code. Additionally frequent job rotations are the best way to increase salary resulting in less experienced developers that stay on the team.

It makes sense to visualize the relevant architecture to avoid this. Dependency graphs can prevent someone from making breaking changes to a piece of code and visualizations that capture the overall architecture of a project help to identify areas of improvement. Having tools for that purpose can aid in developing a sustainable and extendable product from the first line of code significantly improving ramp up time on new developers overall improving the code quality.

## Evolution

Very few software products are developed once, deployed and then never altered again. Most of them are in a state of constant evolution with weekly or even nightly builds being released to users. In that context it could be beneficial to review the evolution of the project, analysing how the project changed over time and what outside and internal factors led to improvements of downfalls.

At employee level these statics can help to identify quality contributors and retaining valuable developers by distributing budget accordingly. A employee who feels unseen and unvalued is likely to consider switching jobs potentially harming the projects development. It is also advisable to find repeating negative or positive patterns and adjusting aims and responses to those in real time.

On a technical level bigger projects almost always leverage libraries and frameworks that combine frequently needed functionality. These libraries that are continuously developed as well might introduce breaking changes or labelling functionality as deprecated. Without an overview on what might change in the future the stability of production code might be endangered. It's a tedious job to crawl all existing code when a library announces deprecations and it's a security hazard to continue to use outdated versions without security updates.  