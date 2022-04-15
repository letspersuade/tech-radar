# Persuade's Tech Radar

The [Tech Radar](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fraw.githubusercontent.com%2Fletspersuade%2Ftech-radar%2Fmain%2Fradar.csv) describes the technology landscape through a Persuade lens. We've made this repo public partly because it helps us use the technology that generates the radar, and partly because it's interesting to see the technology we use at Persuade.

We capture technology in one of four categories:
* **Languages and Frameworks**. Languages and frameworks that we use when building products.
* **Tools**. These can be components, such as databases, software development tools, such as versions control systems; or more generic categories of tools, such as the notion of polyglot persistence.
* **Platforms**. Things that we build software on top of such as .NET, SQL Server, Windows (etc).
* **Techniques**. These include elements of a software development process, such as experience design; and structuring software, such as microservices.

Items on the Tech Radar should only be captured if the cost of change is high or the benefits of standardizing outweigh the drawbacks. Each item on the tech radar should be there for the the good of Persuade or our customers.

Each technology choice is positioned in one of four areas.
* **Adopt** – We feel strongly that Persuade and our clients should be adopting these items. It’s the default choice.
* **Trial** – Worth pursuing. It’s important to understand how to build up this capability. Persuade's teams can try this technology on a project that can support the risk.
* **Assess** – Worth exploring with the goal of understanding how it will affect Persuade and our clients.
* **Hold** - Proceed with caution

The Tech Radar doesn’t provide all the answers, but it should give strong direction in those areas where choice makes a difference.

We're following Thoughtworks approach. For discussion on the quadrants, please see the [Thoughtworks Radar Faq](https://www.thoughtworks.com/radar/faq)

## Who builds the radar?

The radar is open for anyone within Persuade to contribute. Before contributing please read the [Contributing Guidelines](.github/CONTRIBUTING.md).

The recommended way to propose a change or spark a discussion is to open a PR. Contributions should be promptly reviewed by a PSE or Practice lead in the relevant domain. Comments from all other interested parties are more than welcome.

## How is the radar built?

We use [Thoughtworks Tech Radar](https://radar.thoughtworks.com/) to generate our Tech Radar. The radar is backed by a single CSV file (that should nicely [render](https://help.github.com/articles/rendering-csv-and-tsv-data/)). CSV files are parsed using `d3.js` so please see their [documentation](https://d3-wiki.readthedocs.io/zh_CN/latest/CSV) for escaping rules. All changes to the Tech Radar should be completed via a PR and merged by someone else.

You can see the latest version at [https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fraw.githubusercontent.com%2Fletspersuade%2Ftech-radar%2Fmain%2Fradar.csv](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fraw.githubusercontent.com%2Fletspersuade%2Ftech-radar%2Fmain%2Fradar.csv).