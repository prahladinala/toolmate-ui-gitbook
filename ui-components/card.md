# Card

## UI Components/Cards

### Basic Card

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

```html
<div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md p-5">
  <h5 class="text-lg font-bold text-gray-900">Card Title</h5>
  <p class="text-gray-700 mt-2">
    This is a simple description for the card component.
  </p>
  <button
    type="button"
    class="mt-4 w-full bg-blue-600 text-white font-semibold py-2 px-4 rounded hover:bg-blue-700"
  >
    Learn More
  </button>
</div>
```

### Card with Image

<figure><img src="../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

```html
<div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md overflow-hidden">
  <img class="w-full h-48 object-cover" src="https://via.placeholder.com/300" alt="Card image" />
  <div class="p-5">
    <h5 class="text-lg font-bold text-gray-900">Card Title</h5>
    <p class="text-gray-700 mt-2">
      This is a simple description for the card component.
    </p>
    <button
      type="button"
      class="mt-4 w-full bg-blue-600 text-white font-semibold py-2 px-4 rounded hover:bg-blue-700"
    >
      Learn More
    </button>
  </div>
</div>
```

### Horizontal Card

<figure><img src="../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

```html
<div class="flex bg-white border border-gray-200 rounded-lg shadow-md overflow-hidden max-w-2xl">
  <img class="w-1/3 object-cover" src="https://via.placeholder.com/150" alt="Card image" />
  <div class="p-5 w-2/3">
    <h5 class="text-lg font-bold text-gray-900">Horizontal Card Title</h5>
    <p class="text-gray-700 mt-2">
      This is a description for a horizontal card layout.
    </p>
    <button
      type="button"
      class="mt-4 bg-blue-600 text-white font-semibold py-2 px-4 rounded hover:bg-blue-700"
    >
      Learn More
    </button>
  </div>
</div>
```

### Card with Icon and Buttons

<figure><img src="../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>

```html
<div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md p-5 text-center">
  <div class="flex justify-center items-center mb-4">
    <svg class="w-10 h-10 text-blue-600" fill="currentColor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
      <path d="M12 2a10 10 0 100 20 10 10 0 000-20zM11 6h2v6h-2zm0 8h2v2h-2z" />
    </svg>
  </div>
  <h5 class="text-lg font-bold text-gray-900">Info Card</h5>
  <p class="text-gray-700 mt-2">
    This is a card with an icon and multiple buttons.
  </p>
  <div class="mt-4 flex space-x-2">
    <button
      type="button"
      class="bg-blue-600 text-white font-semibold py-2 px-4 rounded hover:bg-blue-700"
    >
      Accept
    </button>
    <button
      type="button"
      class="bg-red-600 text-white font-semibold py-2 px-4 rounded hover:bg-red-700"
    >
      Decline
    </button>
  </div>
</div>
```

### Profile Card

<figure><img src="../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

```html
<div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow-md text-center p-5">
  <img
    class="w-24 h-24 rounded-full mx-auto mb-4"
    src="https://via.placeholder.com/150"
    alt="Profile picture"
  />
  <h5 class="text-lg font-bold text-gray-900">John Doe</h5>
  <p class="text-gray-700 mt-2">Software Engineer</p>
  <p class="text-gray-500 mt-2">john.doe@example.com</p>
  <button
    type="button"
    class="mt-4 bg-blue-600 text-white font-semibold py-2 px-4 rounded hover:bg-blue-700"
  >
    Follow
  </button>
</div>
```

### Gradient Card

<figure><img src="../.gitbook/assets/image (5) (1).png" alt=""><figcaption></figcaption></figure>

```html
<div class="max-w-sm p-5 rounded-lg shadow-md text-white bg-gradient-to-r from-purple-500 to-indigo-600">
  <h5 class="text-lg font-bold">Gradient Card Title</h5>
  <p class="mt-2">
    This card has a gradient background and is great for making content stand out.
  </p>
  <button
    type="button"
    class="mt-4 bg-white text-purple-600 font-semibold py-2 px-4 rounded hover:bg-gray-100"
  >
    Get Started
  </button>
</div>
```

