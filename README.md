Demo app to show crash. To reproduce:
1) Open second fragment by clicking a button 
2) Quickly press back button

You will get `java.lang.IllegalStateException: my_text_view must not be null` in [this line](https://github.com/PiN73/TestKotlinViewBinding/blob/3d340963f0e9411778facce4afa3c7a6fb0be418/app/src/main/java/p/testkotlinviewbinding/SecondFragment.kt#L28).
