# CS-360-Module-8
Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The goals of my app is to be able for users to set action items and recieve notifications for them. The requirements focused on speed, reliability, and privacy. I wanted offline-first storage so entries never disappeared, clear reminders so I wouldn’t miss things, and only the permissions that truly matched the features. 

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The screens and features that were necessary were a home list/grid to wirte upcoming items, an add/edit screen on the same page. A page for permissions area to manage notifications or SMS options. It keeps users in mind by making it very simple to use. It was successful because users found their way around the app without any problems. 

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

I approached the process of coding the app by starting with the design first by creating the xml files then making the java files once I had a design. The main strategies I used were to build the smallest usable slice, test it, and iterate; to keep logic separate from views so changes didn’t ripple everywhere. These same habits will scale to future projects because they make features easier to add, review, and test.

How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

I tested it to ensure it was functional by using the emulator. I was adding/editing/deleting events, denying permissions to see graceful fallbacks, and checking that data persisted across app restarts. It is important because it revealed issues early on in the developement. By testing I saw that I had an issue with editing the existing action items. 

Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

The place I needed to innovate was around permissions and speed. I switched to requesting permissions only at the point of need.

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

The component I’m most proud of is the data layer plus the “Add Event” flow. The Room setup made the app feel solid and trustworthy, and the streamlined add screen delivered on the main promise. 
