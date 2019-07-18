---
layout: post
title:  React Native at The NetCircle
date:   2018-07-04 12:00:00 +0800
---

_Orignal post at [TheNetCircle company website](https://thenetcircle.com/updates/research-sharing-react-native/)._

<iframe src="https://slides.com/timwangdev/react-native-at-dating-framework/embed" width="678" height="464" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

**_Note:_**

When we started the new app project at Dating Framework Team, we did a lot of researches on cross-platform solutions. Soon, React Native stood out as the most promising one, based on its large community and fast iteration speed. In this blog, I’d like to share our experience with React Native, the challenges we took and the problems we solved in almost one year.

Since it was a complete new project, we got to make an aggressive choice between many new tech stacks and try out some experiments at the beginning. Later, we also found a TypeScript, React Native, Redux, React Navigation, Realm stack is quite agreeable to our needs.

Code-sharing and the open source community are two of our strong suits which enable us to achieve up to 100% share rate in TypeScript code. We also love the performance of React and the ability to integrate with native modules. We introduced TypeScript to the project to fix some of the JavaScript problems, although some extra setup steps were required when binding with react-native bundler system. We have been forking and patching broken npm modules pro-actively to fix package issue. And we also contribute back to the OSS community by make pull requests upstream when appropriate.

With the native development experience still being an issue of React Native due to a lack of documentations and breaking changes across each upgrade, we still managed to provide some workarounds at last to avoid those inevitables.

Overall, React Native is a great framework and we enjoy the whole development process under it at Dating Framework Team. The idea of universal UI Development the framework brought with is always inspiring our team, so we’d love to explore more of what this stack could evolve within our team.

