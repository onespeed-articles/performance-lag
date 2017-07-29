## Prevent JavaScript Performance Lag

You know the story. The one where the dev poured all this time and effort into that new greenfield project with the shiny paint job. Features are mostly done and this thing is ready to ship. They minified their JavaScript and CSS just like they were supposed to. App gets deployed just to find out that it takes 30 seconds to load on 3G mobile. The app can't handle more than 1k request per second, even with the API cached. There is so much jank when scrolling that its blank in Safari. Performance lag, because there is much lag to when performance is considered, if at all. Performance lag can seem to come from out of nowhere and completely freeze a project while increasing costs and pushing deadlines back. No one wants this. We see more and more cases of performance lag with JavaScript Apps, mainly because things change so fast, it can be difficult for performant patterns to emerge for a technology, if at all. Performance lag can and should be avoided at all costs, here's how.

## Performance is a required feature
Depending on you and or your team's process, you probably have some sort of organization around how tasks are completed. As you begin to plan out those tasks, make sure you include performance as one of those tasks. Doing this from the beginning will help eliminate performance lag. Remember, performance is ongoing. There is no one fit all solution for every JavaScript app out there, but the common solutions solving the common issues will get you far.


## Base performance off data
When scoping out the performance features for your app, you should use things like your traffic data (real or anticipated) to load test your applications. You'll need those baselines to shoot for in your performance testing and to actually complete your performance features.


## Automate performance checking
Who doesn't like to automate things? JavaScript performance can be automated as well. Depending on what tools you use and how your team develops, you should automate when and how performance is checked for your apps. For example, if your team versions the app, and has releases versions here and there. You can trigger a performance test whenever a new version is cut. You can catch performance regression early on too by attaching to master branch pull/merge request too. This all depends on your flow, but JavaScript performance can most definitely be automated.


## Everyone should be involved with performance
You shouldn't have just one person, or group handling all performance, and nothing else. That's also true the other way around, don't have people building all features expect performance. The features that go into your app will affect performance greatly, it's not always the fault of the framework. So it would be beneficial to have the folks creating the features also tuning the performance too. Maybe whenever someone introduces a big feature, there is an accompanying performance tuning/check/regression that is also that person's responsibility. 


## Conclusion
Here at [OneSpeed](https://onespeed.io) we practice all the above to ensure our client's apps and our own, are performant from day one and remain that way. No surprises at the end. Don't fall victim to performance lag on your JavaScript projects, get ahead of it and treat performance as a first class feature. 
