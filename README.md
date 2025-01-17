1) install next.js

2) install @clerk/nextjs

3) import { ClerkProvider } from '@clerk/nextjs'

4) wrap your app in <ClerkProvider>

5) import { SignInButton, SignedIn, SignedOut, UserButton } from '@clerk/nextjs'

6) add middleware.ts to root

7) add signin and signup routing

8) update middleware.ts

9) add .env info

10) wrap ur layout.tsx in a div to center everything and 
implement clerkloaded and clerk loading to figure out when user is finished

11) wrap loaded divs in clerkloaded, seperate other div above clerklaoded with clerk loading and show a ...loading screen until user is loaded 

12) create navbar component in root directory, then link to href='/' home
and create href to sign-in and sign-up and logout

13) 



