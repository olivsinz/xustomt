# Xustomt

Notice: Work In Progress

Custom Shopify Template based on Tailwind CSS

To Build application.css.liquid file and remove any unused Tailwind utility classes, set enabled on the purge object in tailwind.config.js to true and :

```
npx tailwindcss build src/css/application.css -o assets/application.css.liquid
```