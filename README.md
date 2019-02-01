# Awesome LaunchDarkly [![Awesome](https://awesome.re/badge-flat2.svg)](https://launchdarkly.com) [![Join the community on Spectrum](https://withspectrum.github.io/badge/badge.svg)](https://spectrum.chat/launchdarkly)

<br>

[<img src="media/LaunchDarkly_Icon_Navy.svg" align="right" width="100">](https://launchdarkly.com)

> a curated list of how to dark launch

- [Quick Start](https://docs.launchdarkly.com/docs/getting-started)

## Contents

- [Apps](#apps)
- [Articles](#articles)
- [Boilerplates](#boilerplates)
- [Books](#books)
- [Community](#community)
- [Documentation](#documentation)
- [Open Source](#Open-Source)
- [Podcasts](#podcasts)
- [Talks](#Talks)
- [Tips](#tips)
- [Tools](#Tools)
- [Videos](#videos)

## Apps

- [LD Relay on docker hub](https://cloud.docker.com/u/launchdarkly/repository/docker/launchdarkly/ld-relay)
- [yusinto/launchdarkly-app](https://github.com/yusinto/launchdarkly-app) - React Native example app
- [levlaz/ld-ads-node](https://github.com/levlaz/ld-ads-node) - Node Consumer for the LD Analytics Data Stream
- [atrakh/ice-cream-api](https://github.com/atrakh/ice-cream-api) - Feature flags to serve rate limits
- [yusinto/ld-scheduler](https://github.com/yusinto/ld-scheduler) - Schedule LaunchDarkly flags on or off
- [launchdarkly/ld-tour-of-heroes](https://github.com/launchdarkly/ld-tour-of-heroes) - LaunchDarkly with Angular
- [levlaz/LdLambdaNotify](https://github.com/levlaz/LdLambdaNotify) - Process LaunchDarkly webhooks with AWS Lambda
- [ALM-Rangers/azurefunction-vsts-feature-flags](https://github.com/ALM-Rangers/azurefunction-vsts-feature-flags) - building extenstions with feature flags
- [velianarie/graphql-launchdarkly](https://github.com/velianarie/graphql-launchdarkly)
  - with [blog](http://velianarie.blogspot.com/2018/10/feature-toggling-graphql-service-with.html)
- [tdeekens/flopflip](https://github.com/tdeekens/flopflip)
  - with [blog](https://techblog.commercetools.com/embracing-real-time-feature-toggling-in-your-react-application-a5e6052716a9)
- [levlaz/ld-demo-java](https://github.com/levlaz/ld-demo-java) - Java Sandbox

## Articles

- [How Atlassian Uses Feature Management to Continuously Deliver](https://thenewstack.io/how-atlassian-uses-feature-management-to-continuously-deliver/)

- [Feature Toggles (aka Feature Flags)](https://martinfowler.com/articles/feature-toggles.html)

- [Continuous Delivery and Effective Feature Flagging with LaunchDarkly](https://aws.amazon.com/blogs/startups/continuous-delivery-and-effective-feature-flagging-with-launchdarkly/)

- [Feature flagging to mitigate risk in database migration](https://launchdarkly.com/blog/feature-flagging-to-mitigate-risk-in-database-migration/)

- [How LaunchDarkly Serves Over 4 Billion Feature Flags Daily](https://stackshare.io/launchdarkly/how-launchdarkly-serves-over-4-billion-feature-flags-daily)

- [Best Practices for Testing Code Under Feature Flags](https://launchdarkly.com/blog/best-practices-for-testing-code-under-feature-flags/)

- [Deploying new releases: Feature flags or rings?](https://opensource.com/article/18/2/feature-flags-ring-deployment-model)

- [Silicon Valley’s Top Product Managers Use Feature Flags — And You Should Too](https://hackernoon.com/silicon-valleys-top-product-managers-use-feature-flags-and-you-should-too-cc51cc1aeafb)

- [Implementing Feature Flags in Serverless Environments](https://launchdarkly.com/blog/go-serveless-not-flagless-implementing-feature-flags-in-serverless-environments/)

* [Feature Flags Explained: Use Cases, Benefits and Examples](https://taplytics.com/blog/feature-flags-use-cases-benefits/) - Tapalytics

* [How Feature Toggles Expedite Feedback Loop?](https://www.linkedin.com/pulse/how-feature-toggleexpedites-feedback-loop-sagar-rao/)

* [GitHub Actions Controlled with LaunchDarkly](https://launchdarkly.com/blog/github-actions-controlled-with-launchdarkly/)

* [How to implement feature flags and A|B testing](https://blogs.msdn.microsoft.com/visualstudioalmrangers/2017/04/04/how-to-implement-feature-flags-and-ab-testing/)

* [Building VSTS Extensions with feature flags – Part 3](https://blogs.msdn.microsoft.com/visualstudioalmrangers/2017/08/10/building-vsts-extensions-with-feature-flags-part-3/)

* [Buying vs. Building A Feature Flagging System](https://blog.launchdarkly.com/buying-vs-building-a-feature-flagging-system/)

* [Feature Flags: Smaller, Better, Faster Software Development](https://medium.com/@dehora/feature-flags-smaller-better-faster-software-development-f2eab58df0f9)

* [Embracing real-time feature toggling in your React application](https://techblog.commercetools.com/embracing-real-time-feature-toggling-in-your-react-application-a5e6052716a9)

- [Sitecore and Feature Flags using LaunchDarkly](https://briancaos.wordpress.com/2017/03/31/sitecore-and-feature-flags-using-launchdarkly/)

- [Feature Flag-Driven Development](https://dzone.com/articles/feature-flag-driven-development)

- [What's the cost of feature flags?](https://opensource.com/article/18/7/does-progressive-exposure-really-come-cost)

- [How we checked and fixed the 503 error and Performance issue in our Azure Function](https://blogs.msdn.microsoft.com/visualstudioalmrangers/2018/04/03/how-we-checked-and-fixed-the-503-error-and-performance-issue-in-our-azure-function/)

- [When Feature Flags Go Wrong](https://www.infoq.com/articles/feature-flags-gone-wrong) - Power Peg
- [Knight Capital](https://hackernoon.com/the-rise-and-fall-of-knight-capital-buy-high-sell-low-rinse-and-repeat-ae17fae780f6)

- [Designing for Failure to Avoid Disaster](https://launchdarkly.com/blog/designing-for-failure-to-avoid-disaster/)

## Boilerplates

<details><summary>LaunchDarkly SDK Example Apps</summary><br>

- [Android Hello LaunchDarkly](https://github.com/launchdarkly/hello-android)
- [C Hello LaunchDarkly](https://github.com/launchdarkly/hello-c)
- [ColdFusion Hello LaunchDarkly](https://github.com/launchdarkly/hello-cf)
- [Go Hello LaunchDarkly](https://github.com/launchdarkly/hello-go)
- [Java ☕️ Hello LaunchDarkly](https://github.com/launchdarkly/hello-java)
- ## Apple
  - https://github.com/launchdarkly/hello-ios
  - [iOS Hello LaunchDarkly](https://github.com/launchdarkly/hello-ios)
  - [macOS Hello LaunchDarkly ](https://github.com/launchdarkly/hello-macos)
  - [Swift Hello LaunchDarkly](https://github.com/launchdarkly/hello-ios-swift)
  - [tvOS Hello LaunchDarkly](https://github.com/launchdarkly/hello-tvos)
- ## JavaScript
  - [Client-side JavaScript Hello LaunchDarkly](https://github.com/launchdarkly/hello-js)
  - [Electron Hello](https://github.com/launchdarkly/hello-electron)
  - [Node.js Hello LaunchDarkly](https://github.com/launchdarkly/hello-node)
  - [Node.js bootstrapping server-side app LaunchDarkly](https://github.com/launchdarkly/hello-bootstrap)
  - [TypeScript Hello LaunchDarkly](https://github.com/launchdarkly/hello-node-typescript)
- ## Microsoft
  - [dot Net Hello LaunchDarkly ](https://github.com/launchdarkly/hello-dotnet)
  - [Electron Hello](https://github.com/launchdarkly/hello-electron)
  - [TypeScript Hello LaunchDarkly](https://github.com/launchdarkly/hello-node-typescript)
  - [Xamarin Forms Hello LaunchDarkly](https://github.com/launchdarkly/hello-xamarin-forms)
  - [Xamarin Hello LaunchDarkly](https://github.com/launchdarkly/hello-xamarin)
- ## Python
  - [Python Hello LaunchDarkly](https://github.com/launchdarkly/hello-python)
  - [django Hello LaunchDarkly](https://github.com/launchdarkly/hello-python-django)
- ## Ruby
  - [Ruby Hello LaunchDarkly](https://github.com/launchdarkly/hello-ruby)
  - [Rails Hello LaunchDarkly](https://github.com/launchdarkly/hello-bootstrap-rails)

</details>

## Books

- [Effective Feature Management](https://launchdarkly.com/downloads/EffectiveFeatureManagement_LaunchDarkly.pdf)
- [Managing Feature Flags](https://www.oreilly.com/library/view/managing-feature-flags/9781492028598/)

## Documentation

- [launchdarkly/featureflags](https://github.com/launchdarkly/featureflags)
- [LaunchDarkly Docs](https://docs.launchdarkly.com/)
- [LaunchDarkly API Docs](https://apidocs.launchdarkly.com/docs)

## Open Source

- [cryptocurrencytrader/react-launch-darkly](https://github.com/cryptocurrencytrader/react-launch-darkly)
- [TrueCar/react-launch-darkly](https://github.com/TrueCar/react-launch-darkly)
- [lectra-tech/ld-react-feature-flags](https://github.com/lectra-tech/ld-react-feature-flags)
- [yusinto/ld-react](https://github.com/yusinto/ld-react)
- [yusinto/ld-vue](https://github.com/yusinto/ld-vue)
- [launchdarkly-dynamo-store](https://github.com/mlafeldt/launchdarkly-dynamo-store)
- [yusinto/ld-redux](https://github.com/yusinto/ld-redux)

## Tools

- [launchdarkly/ld-vscode](https://github.com/launchdarkly/ld-vscode)
- [coveo/launchdarkly-terraform-provider](https://github.com/coveo/launchdarkly-terraform-provider)
- [mlafeldt/terraform-provider-launchdarkly](https://github.com/mlafeldt/terraform-provider-launchdarkly)
- [launchdarkly/ld-openapi](https://github.com/launchdarkly/ld-openapi)
- [ricardo-ch/xamarin-launchdarkly-ios](https://github.com/ricardo-ch/xamarin-launchdarkly-ios)
- [api-stack-providers/launchdarkly](https://github.com/api-stack-providers/launchdarkly)

## Podcasts

- [To Be Continuous](https://itunes.apple.com/us/podcast/to-be-continuous/id1107185328?mt=2)

## Videos

- Fun Fun Function
  - [Getting Started with Feature Flags](https://www.youtube.com/watch?v=pwA_Ehp2SMY&list=PL0zVEGEvSaeE60rDzztI2hzdyygILQbZj)
  - [Implementing LaunchDarkly](https://www.youtube.com/watch?v=KtFrV5SKu2U)
  - [Incremental rollout and targeting individual users](https://www.youtube.com/watch?v=ilRGOvR4HxU)
    - code [mpj/playlist-app-launchdarkly](https://github.com/mpj/playlist-app-launchdarkly)
- Creative World
  - [Using multivariate feature flags-launchdarkly to drive operational settings like minimum log level](https://www.youtube.com/watch?v=ywAqg81B3To)
  - [Using launchdarkly to target personally identifiable information pii during feature flag evaluation](https://www.youtube.com/watch?v=LW_d4g_ixyE&)
  - [Using The LaunchDarkly Dashboard And JSON Types To Create Light Weight Application Administrative Features](https://www.youtube.com/watch?v=fH6KbCArpeY&)
  - [Using Multivariate Feature Flags In LaunchDarkly To Gradually Ramp-Up Batched Operations](https://www.youtube.com/watch?v=JfE-Vrx3QKY&index=4&list=PLIanSM0P2mc2sp05s9O-8ZGZygZFP604U)

## Talks

- [Removing Risk from Product Launches with CircleCI, GoPro, and LaunchDarkly](https://youtu.be/mJEZ8-PfTjk)
- [SOC2 is not a 4 letter word: A startup guide to compliance](https://www.youtube.com/watch?v=YIjMPGoW9nI)
- [The Sticker Talk ](https://www.youtube.com/watch?v=Nmcasxb6naU&index=20&list=PLFZp20iCJu9zW--E7vbEDUn_glODEZkvp)
- [How Atlassian Does DevOps Webinar - Building Products](https://www.youtube.com/watch?v=px0UwV-W9hA&list=PLFZp20iCJu9zW--E7vbEDUn_glODEZkvp)
- [Deployment Best Practices w/ HashiCorp, Heptio, & LaunchDarkly, DevGuild: Enterprise-Ready Products](https://www.youtube.com/watch?v=QG6vsbGQUeE&index=18&list=PLIanSM0P2mc3MHKdyolkN7r1m744IHWvp)
- [10 Ways to Use Feature Flags](https://www.mindtheproduct.com/2017/01/10-ways-use-feature-flags/)

## Community

- [Discuss](https://spectrum.chat/launchdarkly)
- [Stack Overflow](https://stackoverflow.com/search?tab=votes&q=%22feature%20flag%22)
- [`@launchdarkly` on Twitter](https://twitter.com/launchdarkly)
- [Product Hunt](https://www.producthunt.com/posts/launchdarkly-2)

## Tips

- Contribute some ;)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[Apache License Version 2.0](LICENSE)
