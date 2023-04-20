# DevOps Working Group

This is where the Open edX DevOps working group gathers to work on all matters related to the technical operations of an Open edX platform, both in development and in production.

The DevOps working group is an umbrella for multiple, more specific projects. See the full list below.

## Useful links

- Communication:
    - The Open edX forum [DevOps working group category](https://discuss.openedx.org/c/working-groups/devops), which is the primary communication channel for this working group. Members are encouraged to subscribe to the notifications for this category ("Watch first post").
    - We also use Slack for quick one-off Q&A: see the [#wg-devops](https://app.slack.com/client/T02SNA1T6/C04J9GTLHH8) channel (if you're not already on the Open edX Slack [get an invitation here](https://openedx.org/slack)). Slack is great for talking to individual people, but most in-depth conversations should happen on the forum or on repository tickets.
- Issue management: we use this [project board](https://github.com/orgs/openedx/projects/42)
- General information and Confluence workspaces:
    - [DevOps working group workspace](https://openedx.atlassian.net/wiki/spaces/COMM/pages/3620044867/DevOps+Working+Group) (we try to use it as little as possible and keep most of the information in the forum or in this GitHub project)
    - List of all [Open edX working groups](https://openedx.atlassian.net/wiki/spaces/COMM/pages/46793351/Open+edX+Working+Groups)

## Projects

### Build/Test/Release working group

- General information: [Build/Test/Release workspace](https://openedx.atlassian.net/wiki/spaces/COMM/pages/1022099494/Build-Test-Release+Working+Group)
- Communication: [Build/Test/Release](https://discuss.openedx.org/c/working-groups/build-test-release) working group forum category and #wg-build-test-release Slack channel.
- Issue management: [project board](https://github.com/orgs/openedx/projects/28/views/15)

### Developer Experience working group

- General information: [Developer Experience workspace](https://openedx.atlassian.net/wiki/spaces/COMM/pages/3583016961/Developer+Experience+Working+Group)
- Communication: [Developer Experience](https://discuss.openedx.org/c/working-groups/dev-experience) working group forum category and #wg-developer-experience Slack channel.
- Issue management: [Developer Experience working group](https://github.com/orgs/openedx/projects/37)

### Large Instances working group

- General information: [Large Instances workspace](https://openedx.atlassian.net/wiki/spaces/COMM/pages/3655008783/Large+Instances+-+DevOps+Sub-Working+Group)
- Communication: [bi-weekly meeting](https://discuss.openedx.org/t/deploying-open-edx-on-kubernetes-using-helm/8771), [DevOps](https://discuss.openedx.org/c/operators/7) forum category, [#wg-devops](https://openedx.slack.com/channels/wg-devops) Slack channel.
- Issue management: [Large Instances working group](https://github.com/orgs/openedx/projects/42/views/2)

This group leads the Harmony Kubernetes project, used to deploy Open edX via Helm & Tutor: https://github.com/openedx/openedx-k8s-harmony

### Tutor

Tutor is the default community distribution to run Open edX, both as a development environment and a production platform, using either docker-compose or Kubernetes. The Tutor code base is split into Tutor core and the official plugins.

- Tutor core source code: https://github.com/overhangio/tutor/
- [Documentation](https://docs.tutor.overhang.io/)
- [Project board](https://github.com/orgs/overhangio/projects/4)
- Tutor-related questions are tagged with "tutor" on the forum: https://discuss.openedx.org/tag/tutor
- Become a [Tutor maintainer](https://discuss.openedx.org/t/tutor-maintainers/7287)

## Contributing

### How to join the working group?

We're glad you want to help :) Working group membership is fluid, which means that if you help the group then you are considered a member. All members are strongly encouraged to join the conversation (see the links above). You can reply to an existing topic or write a new topic where you introduce yourself and describe how you would like to help. Welcome!

### How to report an issue?

Would you like to report a devops-related issue? First, check whether the issue was already reported elsewhere:

- Search the [Open edX forum](https://discuss.openedx.org).
- Search the existing issues in this project and the relevant child projects (see links above).

If your issue was already reported, feel free to join the conversation! If your issue is new, then you are strongly encouraged to discuss it in the forum first. You should strive to describe your issue as thoroughly as possible:

- Nobody likes one-line issues! As a rule of thumb, you should expect that other contributors will not put in more work to resolve your issue than you did in describing it.
- Include a precise description of the context in which the error is occurring: what command are you running? What is the url of the page that is crashing?
- Describe the problem precisely: include any error log, stacktrace and browser screenshots. As far as possible, use copy-pasted text instead of screenshots for errors.
- What version of Open edX/Tutor are you running? Are any plugins enabled?
- If relevant, post your OS and browser versions.
- Add your forum topic to the "working groups -> DevOps" forum subcategory such that other members of the group receive a notification.

If you are positive that the issue is relevant for many Open edX users, then you can open a [GitHub issue](https://github.com/openedx/wg-devops/issues). The same recommendations above apply.

### How to get started fixing issues?

Awesome! Have a look at the following issues:

- DevOps ["good first issues"](https://github.com/openedx/wg-devops/issues?q=is%3Aopen+is%3Aissue+label%3Agood-first-issue)
- Build/Test/Release [bugs](https://github.com/openedx/build-test-release-wg/issues?q=is%3Aopen+is%3Aissue+label%3Abug)
- Developer Experience ["good first issues"](https://github.com/openedx/wg-developer-experience/issues?q=is%3Aopen+is%3Aissue+label%3Agood-first-issue)
- Large Instances ["good first issues"](https://github.com/orgs/openedx/projects/42/views/3)
- Tutor ["good first issues"](https://github.com/orgs/overhangio/projects/4/views/1?filterQuery=-label%3A%22good+first+issue%22) (check the "Backlog" column)
Also, read the Open edX [Contributing Guidelines](https://github.com/openedx/.github/blob/master/CONTRIBUTING.md) document.

We're happy to have you on board :)
