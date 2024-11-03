# Alert

## UI Components/Alerts

### Base Alert Component

<figure><img src="../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

```html
<div class="flex items-center space-x-2 rounded-md p-4 text-sm font-semibold shadow-md">
  <svg class="h-5 w-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
    <!-- Icon paths go here -->
  </svg>
  <span>Alert Message</span>
</div>

```

### Alert Variations

<figure><img src="../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

```html
<!-- Success Alert -->
<div class="flex items-center space-x-2 rounded-md bg-green-100 p-4 text-green-800 text-sm font-semibold shadow-md">
  <svg class="h-5 w-5 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4"></path>
  </svg>
  <span>Success! Your action was successful.</span>
</div>

<!-- Warning Alert -->
<div class="flex items-center space-x-2 rounded-md bg-yellow-100 p-4 text-yellow-800 text-sm font-semibold shadow-md">
  <svg class="h-5 w-5 text-yellow-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4m0 4h.01"></path>
  </svg>
  <span>Warning! Please check the information provided.</span>
</div>

<!-- Error Alert -->
<div class="flex items-center space-x-2 rounded-md bg-red-100 p-4 text-red-800 text-sm font-semibold shadow-md">
  <svg class="h-5 w-5 text-red-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4m0 4h.01"></path>
  </svg>
  <span>Error! Something went wrong. Try again.</span>
</div>

<!-- Info Alert -->
<div class="flex items-center space-x-2 rounded-md bg-blue-100 p-4 text-blue-800 text-sm font-semibold shadow-md">
  <svg class="h-5 w-5 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 16h-1v-4h-1m0-4h.01"></path>
  </svg>
  <span>Info: Here is some additional information.</span>
</div>

```

### Interactive Close Button&#x20;

<figure><img src="../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

```html
<div class="flex items-center justify-between space-x-2 rounded-md bg-green-100 p-4 text-green-800 text-sm font-semibold shadow-md">
  <div class="flex items-center space-x-2">
    <svg class="h-5 w-5 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4"></path>
    </svg>
    <span>Success! Your action was successful.</span>
  </div>
  <button class="text-green-600 hover:text-green-800 focus:outline-none">
    <svg class="h-5 w-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
    </svg>
  </button>
</div>

```

