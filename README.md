# angular-questions

single page application

JIT vs AOT



JIT - Compile TypeScript just in time for executing it.

Compiled in the browser.
Each file compiled separately.
No need to rebuild after changing your code and before reloading the browser page.
used in local development.

AOT - Compile TypeScript during build phase.

Compiled by the machine itself, via the command line.
Faster than JIT.
All code compiled together.
No need to deploy the compiler.
More secure, original source not disclosed.
used in production builds.


SPA 
 It does not need page reloading during its usage, and most of its content remains the same while only some of it needs updating.
 When the content needs to be updated, the SPA does it through JavaScript APIs.
 performance increases, and you feel like using a native application.
