# Submit your project

We gather most details about Common Fund projects automatically from NIH systems, but there are some pieces of info that require manual actions to be integrated.
If you would like your project to be included in the dashboard to the fullest extent, please follow the instructions in the sections below as applicable.
We've tried to make this process as easy and automated as possible.

Once you've made a submission (and once your project is in NIH systems), your project should appear here the next time our ingest process runs.
We try to run the ingest process regularly and frequently, but if you'd like your project to show up faster or are otherwise having issues, please [contact us](#contact).

## Submit software repositories

Repositories ("repos") are places for storing, tracking changes to, and collaborating on software.

Currently, we only take submissions of software kept in _public_ GitHub.com repos.
Private repos and other platforms such as GitLab aren't supported yet.

1. Find all GitHub repos that are associated with your project.
   1. If you're unsure where to find these, ask members of your project about any software that was written in support of it, and where the code for the software resides.
1. "Tag" each repo with the project.
   1. See [GitHub's instructions for tagging repos](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics) for reference.
   1. On the main page of the repo, click on the gear ⚙ next to "About".
   1. Under "Topics", type in your _core project number_†, e.g. `U54OD036472` (case-insensitive).

[This repository itself](https://github.com/nih-cfde/icc-eval-core) has been [tagged with its core project number](https://github.com/topics/u54od036472), so use it as a reference.

† Do not confuse this with a (sub) "project" number, which is longer, e.g. `1U54OD036472-01`.

## Submit analytics

Analytics are services that monitor traffic (number of visits over time, number of unique visitors, visitor demographics, etc.) on publicly accessible webpages.

Currently, we only take submissions of webpages using Google Analytics.
Other analytics services may supported in the future.

1. Find all Google Analytics properties that are associated with your project.
   1. If you're unsure where to find these, ask members of your project about any webpages related to it, and if anyone set up analytics for them.
1. Allow us access to each property.
   1. Go to the [Google Analytics dashboard](https://analytics.google.com/) and make sure you are [on the right property](https://support.google.com/analytics/answer/10252712?hl=en).
   1. Find "Property Access Management" from the main search bar (or the "Admin" side menu).
   1. Add a new user with the email `api-access@cfde-icc-eval-core-433116.iam.gserviceaccount.com`, uncheck "Notify by email", and select the "Viewer" role.
1. "Tag" each property so we can associate it with a particular project.
   1. Find "Key Events" from the "Admin" side menu,under "Data Display".
   1. Create a new key event with the name `cfde_XXX` (case-insensitive), where XXX is the _core_ project number, e.g. `cfde_R03OD034502`.
