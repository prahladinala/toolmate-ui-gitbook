# Banner

## UI Components/Banner

### Simple Notification Banner

<figure><img src="../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

```html
<div class="bg-blue-600 text-white py-3 px-4 text-center text-sm font-semibold">
  Welcome to our website! Get 10% off your first purchase.
</div>
```

### Banner with Close Button

<figure><img src="../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

```html
<div class="bg-indigo-600 text-white py-3 px-4 flex items-center justify-between">
  <span class="text-sm font-medium">Check out our latest features!</span>
  <button class="text-white hover:bg-indigo-700 rounded-full p-1 focus:outline-none">
    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
    </svg>
  </button>
</div>
```

### Banner with Button

<figure><img src="../.gitbook/assets/image (2) (1) (1).png" alt=""><figcaption></figcaption></figure>

```html
<div class="bg-purple-600 text-white py-3 px-4 flex items-center justify-between">
  <span class="text-sm font-medium">Limited time offer! Get 20% off all items.</span>
  <a href="#" class="ml-4 px-3 py-2 bg-purple-800 rounded text-white font-semibold text-xs hover:bg-purple-700">
    Shop Now
  </a>
</div>
```

### Fixed Banner on top

<figure><img src="../.gitbook/assets/image (3) (1) (1).png" alt=""><figcaption></figcaption></figure>

```html
<div class="fixed top-0 w-full bg-blue-600 text-white py-3 px-4 text-center text-sm font-semibold z-50">
  We’ve launched our new feature! Check it out now.
</div>
<div class="pt-16">
  <!-- Main page content goes here -->
</div>
```

### Banner with icon

<figure><img src="../.gitbook/assets/image (4) (1) (1).png" alt=""><figcaption></figcaption></figure>

```html
<div class="bg-blue-50 border-l-4 border-blue-400 p-4 flex items-center">
  <svg class="h-5 w-5 text-blue-400 mr-2" fill="none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" stroke="currentColor">
    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 16h-1v-4h-1m1-4h.01M12 19c4.418 0 8-3.582 8-8s-3.582-8-8-8-8 3.582-8 8 3.582 8 8 8z" />
  </svg>
  <p class="text-sm text-blue-700">New updates are available! Refresh the page to get the latest version.</p>
</div>
```

### Banner variations

<figure><img src="../.gitbook/assets/image (5) (1).png" alt=""><figcaption></figcaption></figure>

```html
<div class="space-y-2">
  <div class="bg-green-100 border-l-4 border-green-500 text-green-700 p-4">
    <p class="font-bold">Success</p>
    <p>Your order has been placed successfully.</p>
  </div>
  <div class="bg-yellow-100 border-l-4 border-yellow-500 text-yellow-700 p-4">
    <p class="font-bold">Reminder</p>
    <p>Your subscription is about to expire soon.</p>
  </div>
  <div class="bg-red-100 border-l-4 border-red-500 text-red-700 p-4">
    <p class="font-bold">Error</p>
    <p>There was an error processing your payment. Please try again.</p>
  </div>
  <div class="bg-blue-100 border-l-4 border-blue-500 text-blue-700 p-4" role="alert">
    <p class="font-bold">Info</p>
    <p>New updates are available! Refresh the page to get the latest version.</p>
  </div>
</div>
```

