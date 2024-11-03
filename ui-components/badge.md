# Badge

## UI Components/Badge

### Basic Badge

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

```html
<span class="inline-flex items-center px-2 py-1 rounded-full text-xs font-medium bg-gray-200 text-gray-800">
  New
</span>
```

### Badge with Icon

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

```html
<span class="inline-flex items-center px-2 py-1 rounded-full text-xs font-medium bg-blue-500 text-white">
  <svg
    xmlns="http://www.w3.org/2000/svg"
    class="h-4 w-4 mr-1"
    fill="none"
    viewBox="0 0 24 24"
    stroke="currentColor"
  >
    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
  </svg>
  Verified
</span>

```

### Status Indicator Badge

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

```html
<span class="inline-flex items-center px-2 py-1 rounded-full text-xs font-medium bg-green-100 text-green-800">
  Online
</span>
<span class="inline-flex items-center px-2 py-1 rounded-full text-xs font-medium bg-yellow-100 text-yellow-800">
  Busy
</span>
<span class="inline-flex items-center px-2 py-1 rounded-full text-xs font-medium bg-red-100 text-red-800">
  Offline
</span>
```

### Notification Badge (Counter)

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

```html
<div class="relative inline-block">
  <button type="button" class="inline-flex items-center justify-center h-10 w-10 rounded-full bg-gray-200">
    <svg
      xmlns="http://www.w3.org/2000/svg"
      class="h-6 w-6 text-gray-800"
      fill="none"
      viewBox="0 0 24 24"
      stroke="currentColor"
    >
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 17h5l-1.405 1.405A2.032 2.032 0 0116.25 20H7.75a2.032 2.032 0 01-1.344-.595L5 17h5m5-5V7a5 5 0 00-10 0v5m-2 2h14" />
    </svg>
  </button>
  <span class="absolute top-0 right-0 inline-flex items-center justify-center px-1.5 py-0.5 text-xs font-bold leading-none text-white transform translate-x-1/2 -translate-y-1/2 bg-red-600 rounded-full">
    3
  </span>
</div>
```

### Rounded Badge with Text

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

```html
<span class="inline-block px-3 py-0.5 rounded-lg text-xs font-bold bg-purple-500 text-white">
  Pro
</span>
```

### Badge with Close Icon

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

```html
<span class="inline-flex items-center px-2 py-1 rounded-full text-xs font-medium bg-gray-200 text-gray-800">
  Filter
  <button type="button" class="ml-1 inline-flex items-center justify-center rounded-full text-gray-500 focus:outline-none focus:text-gray-700">
    <svg
      xmlns="http://www.w3.org/2000/svg"
      class="h-3 w-3"
      viewBox="0 0 20 20"
      fill="currentColor"
    >
      <path
        fill-rule="evenodd"
        d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
        clip-rule="evenodd"
      />
    </svg>
  </button>
</span>
```

