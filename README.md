A script to add Tailwind CSS and PurgeCSS to your Rails 6 application

In your rails app directory, run
```rails app:template LOCATION="https://railsbytes.com/script/zyvs0r"```

### Note
- If you've changed your postcss.config.js, this script will overwrite the file. Make note of your changes and add them back.
- You will have to remove 'app/assets/stylesheets/scaffold.scss' as it messes
with Tailwind CSS

### Testing
Add the code below to one of your templates and run `rails server`
```
<div>
  <textarea class="resize-y border rounded focus:outline-none focus:shadow-outline" placeholder="resize y"></textarea>
</div>

<svg class="animate-bounce w-6 h-6 text-gray-900" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor">
  <path d="M19 14l-7 7m0 0l-7-7m7 7V3"></path>
</svg>

<p class="text-purple-700 text-opacity-100">The quick brown fox ...</p>
<p class="text-purple-700 text-opacity-75">The quick brown fox ...</p>
<p class="text-purple-700 text-opacity-50">The quick brown fox ...</p>
<p class="text-purple-700 text-opacity-25">The quick brown fox ...</p>
<p class="text-purple-700 text-opacity-0">The quick brown fox ...</p>
```

If it doesn't work, refresh the page or restart your rails server.
