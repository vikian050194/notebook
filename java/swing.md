# Java Swing

UPD: Initial title was "How to build desktop app in 2024".

Initially I have tried to make "Hello, World!" app using:

* `Electron` - no, it's too complex to work with background worker;
* `Neutralinojs` - no, I have problems with samples compiling and running.

Other possible declined options:

* `Qt` is not an option, because I do not want to use C++;
* `WinForms/WPF/UWA/UWP` is not an option, because I do not want to return to C#;
* `Tkinter` or `PyQt` is not an option because I do not want to use Python for such complex application.

Selected options:

* `AWT` is OK for first MVP. I already have some examples and small experience with it after `Java: The Complete Reference, Twelfth Edition 12th Edition by Herbert Schildt`;
* `Swing` is "legacy" technology too, but it's OK for me. Some experience and basic examples from book as well. It's good for beginning.

So `Swing`. But more knowledge is needed:

* Few free chapters of [Java Swing by Robert Eckstein, Marc Loy, Dave Wood](https://www.oreilly.com/library/view/java-swing/156592455X/ch01s04.html);
* 💖 [StackOverflow: custom java Swing component Model, UIDelegate, component format](https://stackoverflow.com/questions/26792529/custom-java-swing-component-model-uidelegate-component-format) - good relevant example of Zoom component for images viewing. Copy-pasted into project and refactored;
* [StackOverflow: Proper model-view-controller design](https://stackoverflow.com/questions/2389735/proper-model-view-controller-design) - two links to Martin Fowler in answers;
* 👍 [Martin Fowler: Presentation Model](https://martinfowler.com/eaaDev/PresentationModel.html) - it will wait few more questions on StackOverflow;
* 👍 And this article too - [Martin Fowler: GUI Architectures](https://martinfowler.com/eaaDev/uiArchs.html);
* Again [StackOverflow: Advice welcomed on creating my own Swing component](https://stackoverflow.com/questions/2511270/advice-welcomed-on-creating-my-own-swing-component);
* [StackOverflow: How to use BigDecimal in swing GUIs?](https://stackoverflow.com/questions/2495456/how-to-use-bigdecimal-in-swing-guis) - previous question from the same person;
* [StackOverflow: How to determine the correct UI implementation for a custom component](https://stackoverflow.com/questions/17798631/how-to-determine-the-correct-ui-implementation-for-a-custom-component)
* [StackOverflow: Custom Swing component: questions on approach](https://stackoverflow.com/questions/3001765/custom-swing-component-questions-on-approach)
* [StackOverflow: How to add a progress bar?](https://stackoverflow.com/questions/8916064/how-to-add-a-progress-bar)
* [StackOverflow: Swing - Update Label](https://stackoverflow.com/questions/8916721/swing-update-label/8917565) - example of SwingWorker;
* [StackOverflow: Custom UI in Java Swing](https://stackoverflow.com/questions/65986950/custom-ui-in-java-swing) - bad question style, links to already discovered questions;
* [StackOverflow: custom UI component in java swing](https://stackoverflow.com/questions/16273322/custom-ui-component-in-java-swing) - it's really "basic" question;
* [StackOverflow: Swing Components with custom UI are not painted correctly](https://stackoverflow.com/questions/78407913/swing-components-with-custom-ui-are-not-painted-correctly);
* [StackOverflow: Is it possible to build custom GUI like this in Java?](https://stackoverflow.com/questions/2049015/is-it-possible-to-build-custom-gui-like-this-in-java) - "Oh dear, no-no-no!";
* [Creating a Custom Swing Component
](https://jhippjava.blogspot.com/2011/11/creating-custom-swing-component.html) - it's waste of time;
* [CodeProject: UI Component Development in Java Swing - Part 1: Design](https://www.codeproject.com/Articles/62099/UI-Component-Development-in-Java-Swing-Part-1-Desi) - unfortunately, there is only first part;
* 💖 [Java.net: How to Write a Custom Swing Component](https://web.archive.org/web/20131027161222/http://today.java.net/pub/a/today/2007/02/22/how-to-write-custom-swing-component.html) - it's really cool article, some concepts described better in a bit different way, unfortunetely example sources are missed in time;

UPD: After a while, the quality of the code and its testing began to cause pain. I decided to try to "do everything on the web that can be done there." So...vanilla Java server and almost vanilla JavaScript client.
