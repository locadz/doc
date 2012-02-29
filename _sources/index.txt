.. Locadz documentation master file, created by
   sphinx-quickstart on Wed Feb  8 16:36:04 2012.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


Introduction
============

Locadz is the location-aware advertising platform for your mobile app.

The first time a mobile developer integrates the advertising platform into his app. Usually the developer will
go with the dominant global solution providers like Google AdMob or Apple iAd. These global solution providers
servers advertisements in major markets, but they may not pay you as much as you expected.

And there are domestic niche market players who pay 2 to 5 times more than the global providers do. But the problem
is, if an end user is outside the service area, its traffic are wasted, Niche market provider couldn't display any
relevant ad to this user.

And then the developer may adopt ad rotation tools like AdWhirl. These ad rotation tools split ad traffic. For example,
50% of traffic will go to global provider and the other 50% will go to niche market player. But this isn't solve the
fundamental problem. Still, the end user isn't able to see any relevant ad half of the time.

This is why we create Locadz, the location-aware advertising platform. Locadz allows you to customize the advertisement
provider by location. For example, you can use VPON and domob in China market, adonic in european market, and adMob for
the rest of world. By localizing advertising solutions, you can maximize your ad revenue.

Terminology
-----------

Ad Unit
^^^^^^^

A defined space within an application that has been reserved for the display of advertising. You may define multiple Ad
Units on a single application or screen. For example, one on the top of the screen, one on the bottom of the screen and
another one for the splash screen.

AdUnits are identified by AdUnitId.

AdUnitId
^^^^^^^^

The unique identifier for AdUnit. Do not share your ID with others.

AdBroker
^^^^^^^^


Contents:

.. toctree::
   :maxdepth: 2

   faq.rst
