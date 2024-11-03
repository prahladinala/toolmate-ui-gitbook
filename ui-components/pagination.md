# Pagination

## UI Components/Pagination

### Basic Pagination

<figure><img src="../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

```html
<div class="flex justify-center items-center space-x-4 p-4">
  <button
    class="px-4 py-2 bg-gray-200 rounded-lg hover:bg-gray-300 focus:outline-none focus:ring"
    aria-label="Previous Page"
  >
    Previous
  </button>
  <button
    class="px-4 py-2 bg-gray-200 rounded-lg hover:bg-gray-300 focus:outline-none focus:ring"
    aria-label="Next Page"
  >
    Next
  </button>
</div>

```

### Pagination with Page Numbers

<figure><img src="../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

```html
<div class="flex justify-center items-center space-x-2 p-4">
  <button
    class="px-3 py-2 bg-gray-200 rounded-lg hover:bg-gray-300 focus:outline-none focus:ring"
    aria-label="Previous Page"
  >
    Previous
  </button>
  <button
    class="px-3 py-2 bg-blue-600 text-white rounded-lg hover:bg-blue-700 focus:outline-none focus:ring"
    aria-label="Page 1"
  >
    1
  </button>
  <button
    class="px-3 py-2 bg-gray-200 rounded-lg hover:bg-gray-300 focus:outline-none focus:ring"
    aria-label="Page 2"
  >
    2
  </button>
  <button
    class="px-3 py-2 bg-gray-200 rounded-lg hover:bg-gray-300 focus:outline-none focus:ring"
    aria-label="Page 3"
  >
    3
  </button>
  <span class="px-2">...</span>
  <button
    class="px-3 py-2 bg-gray-200 rounded-lg hover:bg-gray-300 focus:outline-none focus:ring"
    aria-label="Last Page"
  >
    10
  </button>
  <button
    class="px-3 py-2 bg-gray-200 rounded-lg hover:bg-gray-300 focus:outline-none focus:ring"
    aria-label="Next Page"
  >
    Next
  </button>
</div>
```

