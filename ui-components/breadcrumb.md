# Breadcrumb

## UI Components/Breadcrumb

### Basic Breadcrumb

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

```html
<nav class="text-gray-500 text-sm" aria-label="Breadcrumb">
  <ol class="list-none p-0 inline-flex">
    <li class="flex items-center">
      <a href="#" class="text-blue-600 hover:text-blue-700">Home</a>
      <span class="mx-2">/</span>
    </li>
    <li class="flex items-center">
      <a href="#" class="text-blue-600 hover:text-blue-700">Category</a>
      <span class="mx-2">/</span>
    </li>
    <li class="flex items-center">
      <span>Product</span>
    </li>
  </ol>
</nav>
```

### Breadcrumb with Chevron Icon

<figure><img src="../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

```html
<nav class="text-gray-500 text-sm" aria-label="Breadcrumb">
  <ol class="list-none p-0 inline-flex">
    <li class="flex items-center">
      <a href="#" class="text-blue-600 hover:text-blue-700">Home</a>
      <svg class="mx-2 h-4 w-4 text-gray-400" fill="none" stroke="currentColor" stroke-width="2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7" />
      </svg>
    </li>
    <li class="flex items-center">
      <a href="#" class="text-blue-600 hover:text-blue-700">Category</a>
      <svg class="mx-2 h-4 w-4 text-gray-400" fill="none" stroke="currentColor" stroke-width="2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7" />
      </svg>
    </li>
    <li class="flex items-center">
      <span>Product</span>
    </li>
  </ol>
</nav>
```

### Breadcrumbs Bar

<figure><img src="../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

```html
<div class="bg-gray-100 py-3">
  <nav class="text-gray-500 text-sm px-4 max-w-7xl mx-auto" aria-label="Breadcrumb">
    <ol class="list-none p-0 inline-flex">
      <li class="flex items-center">
        <a href="#" class="text-blue-600 hover:text-blue-700">Home</a>
        <span class="mx-2">/</span>
      </li>
      <li class="flex items-center">
        <a href="#" class="text-blue-600 hover:text-blue-700">Category</a>
        <span class="mx-2">/</span>
      </li>
      <li class="flex items-center">
        <span>Product</span>
      </li>
    </ol>
  </nav>
</div>
```

### Responsive Breadcrumb

<figure><img src="../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>

```html
<nav class="text-gray-500 text-sm" aria-label="Breadcrumb">
  <ol class="list-none p-0 flex flex-col sm:flex-row space-y-2 sm:space-y-0 sm:space-x-4">
    <li class="flex items-center">
      <a href="#" class="text-blue-600 hover:text-blue-700">Home</a>
      <span class="hidden sm:inline mx-2">/</span>
    </li>
    <li class="flex items-center">
      <a href="#" class="text-blue-600 hover:text-blue-700">Category</a>
      <span class="hidden sm:inline mx-2">/</span>
    </li>
    <li class="flex items-center">
      <span>Product</span>
    </li>
  </ol>
</nav>
```

