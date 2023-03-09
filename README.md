## Run Locally

Step 1: Fork repository

Step 2: Clone repository

```bash
  git clone https://github.com/ShaileshGodghase/2023
```

Step 3: Create your branch

```bash
  git branch your_name
```

Step 4: Copy below code, fill your details & add your card

```bash
  <div class="flex flex-col mx-auto justify-center max-w-xs p-6 shadow-md rounded-xl sm:px-12 dark:bg-gray-900 dark:text-gray-100">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT4_4cPtcTTnBGx0ismMBL7H54kxLUwEN4aCQ&usqp=CAU"
                alt="" class="w-32 h-32 mx-auto rounded-full dark:bg-gray-500 aspect-square">
            <div class="space-y-4 text-center divide-y divide-gray-700">
                <div class="my-2 space-y-1">
                    <h2 class="text-xl font-semibold sm:text-2xl">{YOUR_NAME}</h2>
                    <p class="px-5 text-xs sm:text-base dark:text-gray-400">{YOUR_COLLEGE}</p>
                </div>
                <div class="flex justify-center pt-2 space-x-4 align-center">
                    <a target="_blank" noopener noreferrer" href="{GITHUB_PROFILE_LINK}"
                        aria-label="GitHub" class="p-2 rounded-md dark:text-gray-100 hover:dark:text-violet-400">
                        <i class="fa-brands fa-github"></i>
                    </a>
                    <a target="_blank" noopener noreferrer" href="mailto:{EMAIL_ID}"
                        aria-label="Dribble" class="p-2 rounded-md dark:text-gray-100 hover:dark:text-violet-400">
                        <i class="fa-solid fa-envelope"></i>
                    </a>
                    <a target="_blank" noopener noreferrer" href="{LINKEDIN_PROFILE_LINK}"
                        aria-label="Twitter" class="p-2 rounded-md dark:text-gray-100 hover:dark:text-violet-400">
                        <i class="fa-brands fa-linkedin"></i>
                    </a>
                    <a target="_blank" noopener noreferrer" href="{WEBSITE_LINK}" aria-label="Email"
                        class="p-2 rounded-md dark:text-gray-100 hover:dark:text-violet-400">
                        <i class="fa-solid fa-globe"></i>
                    </a>
                </div>
            </div>
        </div>
```

Step 5: Add files to stage area

```bash
  git add .
```

Step 6: Create commit

```bash
  git commit -m "card added"
```

Step 7: Push changes

```
  git push -u origin your_branch_name
```

Step 8: Create Pull Request
