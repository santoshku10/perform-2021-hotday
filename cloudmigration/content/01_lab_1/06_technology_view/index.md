## Technologies

By default, Dynatrace gives you FullStack horizontal (who talks to whom) and vertical (what runs on what) dependency visibility as part of Dynatrace Smartscape! All without a single line of code or configuration change – just by installing the OneAgent

Seeing which processes make up the monolith has been an eye-opener for many teams that have done this exercise. “Oh – we completely forgot about the dependency to this legacy process we introduced 5 years ago!” – that’s a common thing you hear!

As you plan your migration, knowing what technologies make up your eco-system is key so what you can decide whether to migrate, refactor or replace certain services.

## 👍 How this helps

This is another out the box feature that helps you understand what technologies are in your environment and with a heatmap presentation to what degree they exist. 

## Review Technologies View

Click on the **Technologies** link on the left side menu within Dynatrace to view the technologies that OneAgent was able to automatically discover and instrument.

![image](../../../assets/images/technology.png)

In the filter box, type `tag`, choose `app`, and the value of `monolith`. It should look like this:

![image](../../../assets/images/technology-filter.png)

The workshop is somewhat limited, so here is an example from another environment.

![image](../../../assets/images/technology-demo.png)
