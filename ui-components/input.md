# Input

## UI Components/Input Fields

### Basic Text Input

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

```html
<div class="flex flex-col mb-4">
  <label for="name" class="mb-2 text-sm font-semibold text-gray-700">Name</label>
  <input
    type="text"
    id="name"
    class="border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-blue-600"
    placeholder="Enter your name"
  />
</div>
```

### Search Input

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

```html
<div class="flex items-center mb-4">
  <input
    type="text"
    class="border border-gray-300 rounded-l-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-blue-600 w-full"
    placeholder="Search..."
  />
  <button class="bg-blue-600 text-white rounded-r-lg px-4 py-2 hover:bg-blue-700 focus:outline-none focus:ring">
    Search
  </button>
</div>
```

### Password Input

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

```html
<div class="flex flex-col mb-4">
  <label for="password" class="mb-2 text-sm font-semibold text-gray-700">Password</label>
  <div class="relative">
    <input
      type="password"
      id="password"
      class="border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-blue-600 w-full"
      placeholder="Enter your password"
    />
    <button class="absolute right-2 top-2 text-gray-500 hover:text-gray-700">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="h-5 w-5"
        fill="none"
        viewBox="0 0 24 24"
        stroke="currentColor"
      >
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4.5C7.5 4.5 3 8.5 3 12s4.5 7.5 9 7.5 9-4.5 9-7.5-4.5-7.5-9-7.5zM12 10.5c-1.5 0-3 1.5-3 3s1.5 3 3 3 3-1.5 3-3-1.5-3-3-3z" />
      </svg>
    </button>
  </div>
</div>
```

### Text Area

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

```html
<div class="flex flex-col mb-4">
  <label for="message" class="mb-2 text-sm font-semibold text-gray-700">Message</label>
  <textarea
    id="message"
    rows="4"
    class="border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-blue-600"
    placeholder="Type your message here..."
  ></textarea>
</div>
```

### Input with Validation Error

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

```html
<div class="flex flex-col mb-4">
  <label for="email" class="mb-2 text-sm font-semibold text-gray-700">Email</label>
  <input
    type="email"
    id="email"
    class="border border-red-500 rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-red-600"
    placeholder="Enter your email"
  />
  <p class="mt-1 text-red-500 text-sm">Please enter a valid email address.</p>
</div>
```

### Input Group with Icons

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

```html
<div class="flex items-center mb-4">
  <span class="bg-gray-200 rounded-l-lg px-4 py-2 text-gray-600">
    <svg
      xmlns="http://www.w3.org/2000/svg"
      class="h-5 w-5"
      fill="none"
      viewBox="0 0 24 24"
      stroke="currentColor"
    >
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14.5 3H9.5a2 2 0 00-2 2v14a2 2 0 002 2h5a2 2 0 002-2V5a2 2 0 00-2-2z" />
    </svg>
  </span>
  <input
    type="text"
    class="border border-gray-300 rounded-r-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-blue-600 w-full"
    placeholder="Enter your input"
  />
</div>
```

