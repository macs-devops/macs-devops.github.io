# What is DataOps?

To understand DataOps, it’s worthwhile to first look at its somewhat more mature counterpart: DevOps.

The term DevOps was coined around 2010 in order to combine development and operations into a single term. Some go so far as to call it a culture. However, for most people, it’s a set of practices and tools that integrates the process of developing and deploying software.

---

* The advent of DevOps was facilitated by several organizational and technological evolutions:

  * :point_right: Agile project methodology and scrum break up work in short iterations (sprints) where all stakeholders work together on the highest priorities.

  * :point_right: Cloud computing and on-demand deployment of computing services enable software developers to deploy their own infrastructure.

  * :point_right: Infrastructure-as-code (IaC) and the provisioning of identical environments make collaborating on the same project within the same conditions less burdensome.

---

* DevOps aims to integrate the processes between software development and IT teams with the two-pronged goal of increasing an organization’s ability to deliver applications at a higher quality and velocity. These goals are achieved through three core principles:

  * :white_check_mark: Collaboration between development and operations

  * :white_check_mark: Automation of the software development lifecycle

  * :white_check_mark: Continuous improvement

* Extrapolate the same goals, principles, and evolutions to data products and you arrive at DataOps: a method to deliver high-quality data products at high velocity. These goals are achieved through:

  * :+1: Close collaboration of data scientists, analysts, data engineers, IT, and quality assurance

  * :+1: Automation throughout the end-to-end analytical process

  * :+1: Continuous improvement and integration of new features into data products

Let’s make it more tangible with an example. Historically, within most organizations, it was hard to set up an automated report like a quarterly sales tracker. And that wasn’t always due to technological constraints. Data needed to be extracted from source systems, transformed, aggregated, made available in an analytical database, and visualized in a business tool. It needed to pass through numerous hands, across several departments. The data used to take months or even years before raw sales figures could be turned into a bar chart. By applying DataOps, organizations can drastically shorten that time to delivery.

## DataOps vs DevOps  

Now you’ve seen that DataOps is the result of applying DevOps principles to the data lifecycle. However, there are considerable differences between the two.

* **Non-Technical Users**  

Within IT and software development, individuals are usually highly technical and they generally have a common set of skills and tools. However, within the data lifecycle, this is rarely the case.

Data analysts and BI engineers work with drag-and-drop dashboarding tools. Even though data scientists are avid coders in Python or R, taking their analysis and resulting algorithms out of a notebook and into deployment is uncommon. For this reason, DataOps tools need to abstract away a lot of the underlying complexity that characterizes a data pipeline.

* **More Exploration**  

Unlike the software development lifecycle, the data lifecycle isn’t a loop. Creating value from data involves a lot of exploration, and not all ideas turn out to be the killer features business users expect them to be. Consequently, lots of exploratory work never reaches the deployment phase.

On the other hand, some data might not exist yet, and setting up the proper data collection or ingestion could delay deployment. Planning resources for DataOps take a lot more flexibility than planning resources for DevOps.

* **Complex Sandboxes**  

Usually, when a software engineer joins a team, he starts with setting up his sandbox. In this isolated development environment, he’ll be able to write and test new features. This sandbox environment is often created in a couple of hours or days via specialized software or by running a couple of scripts.

Sandboxes for data teams are often spread across multiple tools and technologies that can’t be set up at the press of a button. Furthermore, depending on its volume, copying an organization’s data assets can quickly become very expensive. Often representative data sets need to be created.

* **Decentralized Responsibilities**  

Software engineers are often clustered together in the same team or department. However, DataOps needs to account for the fact that analytical roles usually exist in every corner of the organization. It might be adequate to centralize several constituents of the data pipeline, like extracting data from source systems and making them available in a data lake or warehouse. Other parts, like reporting and business intelligence, are often performed in a more efficient manner when they are decentralized.

