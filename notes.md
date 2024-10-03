Boris Ševčík 4.C 2.Skupina

NEXTJS - npx create-next-app@latest

Vytvorenie nového projektu v NEXTJS ;

What is your project named? my-app
Would you like to use TypeScript? No / Yes
Would you like to use ESLint? No / Yes
Would you like to use Tailwind CSS? No / Yes
Would you like your code inside a `src/` directory? No / Yes
Would you like to use App Router? (recommended) No / Yes
Would you like to use Turbopack for `next dev`?  No / Yes
Would you like to customize the import alias (`@/*` by default)? No / Yes
What import alias would you like configured? @/*

cd – change directory
ls – zobrazenie súborov v directory

MUI Components - https://mui.com/material-ui/all-components/

App – Router (Policajt) – rieši iba 3 komponenty – page.tsx, layout.tsx, not-found.tsx

Dev režim – update hned ako sa niečo zmení

Vytvorenie stranky na localhoste:

import Typography from "@mui/material/Typography";

export default function TermsConditions() {
return (
<Typography> Podmienky pouzivania tohto webu </Typography>
);
}

github prikazy :

git init
git branch -m main
git config -- global user.name your name
git config -- global user.email your email
git remote add origin https://github.com/BorisSevcik/zoska-snap.git 
git remote -v (kontrola)
git add .
