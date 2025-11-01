

### SETUP ###
 - pacakge.json
 - global css
 - page.tsx
 - update all and explain the why were needed

 - add daisyui
 - lets see


 ```
"packageManager": "npm@10.5.2",
  "overrides": {
    "react": "$react",
    "react-dom": "$react-dom",
    "next": "$next"
  },

```

### PRISMA DB SETUP ###
- npm i -D prisma
- npm i @prisma/client
- npx prisma init
- npm i @vercel/blob

- bring in vercel
- update the lib directory with prisma.ts function
- can test it out by bringing in the function in the home page
- code:

```

const posts = await prisma.post.findMany()
```

{JSON.stringify(posts)}

- or use.map to get the items

