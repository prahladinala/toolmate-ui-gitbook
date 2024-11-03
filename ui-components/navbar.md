# Navbar

## UI Components/Navbar

### Responsive Navbar with Mobile Toggle

<figure><img src="../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

```html
<nav class="bg-gray-800 p-4">
  <div class="container mx-auto flex justify-between items-center">
    <!-- Brand Name -->
    <a href="#" class="text-white text-lg font-semibold">Brand</a>
    
    <!-- Mobile Toggle Button -->
    <button
      class="text-white md:hidden"
      onclick="document.getElementById('mobile-menu').classList.toggle('hidden')"
    >
      <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
      </svg>
    </button>
    
    <!-- Desktop Links -->
    <div class="hidden md:flex space-x-4">
      <a href="#" class="text-gray-300 hover:text-white">Home</a>
      <a href="#" class="text-gray-300 hover:text-white">About</a>
      <a href="#" class="text-gray-300 hover:text-white">Services</a>
      <a href="#" class="text-gray-300 hover:text-white">Contact</a>
    </div>
  </div>
  
  <!-- Mobile Menu -->
  <div id="mobile-menu" class="hidden md:hidden bg-gray-800 space-y-2 p-4">
    <a href="#" class="block text-gray-300 hover:text-white">Home</a>
    <a href="#" class="block text-gray-300 hover:text-white">About</a>
    <a href="#" class="block text-gray-300 hover:text-white">Services</a>
    <a href="#" class="block text-gray-300 hover:text-white">Contact</a>
  </div>
</nav>
```

### Responsive Navbar with Dropdowns

<figure><img src="../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

```html
<nav class="bg-indigo-600 p-4">
  <div class="container mx-auto flex justify-between items-center">
    <a href="#" class="text-white text-lg font-semibold">Brand</a>
    
    <!-- Mobile Toggle Button -->
    <button
      class="text-white md:hidden"
      onclick="document.getElementById('mobile-menu').classList.toggle('hidden')"
    >
      <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
      </svg>
    </button>
    
    <!-- Desktop Links -->
    <div class="hidden md:flex space-x-4 items-center">
      <a href="#" class="text-white hover:bg-indigo-700 px-3 py-2 rounded">Home</a>
      <div class="relative group">
        <a href="#" class="text-white hover:bg-indigo-700 px-3 py-2 rounded inline-flex items-center">
          Services
          <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
          </svg>
        </a>
        <!-- Dropdown -->
        <div class="absolute hidden group-hover:block bg-white text-gray-700 mt-2 rounded shadow-lg">
          <a href="#" class="block px-4 py-2 hover:bg-indigo-100">Web Development</a>
          <a href="#" class="block px-4 py-2 hover:bg-indigo-100">App Development</a>
          <a href="#" class="block px-4 py-2 hover:bg-indigo-100">SEO Services</a>
        </div>
      </div>
      <a href="#" class="text-white hover:bg-indigo-700 px-3 py-2 rounded">About</a>
      <a href="#" class="text-white hover:bg-indigo-700 px-3 py-2 rounded">Contact</a>
    </div>
  </div>
  
  <!-- Mobile Menu -->
  <div id="mobile-menu" class="hidden md:hidden bg-indigo-600 space-y-2 p-4">
    <a href="#" class="block text-white hover:bg-indigo-700 px-3 py-2 rounded">Home</a>
    <div>
      <a href="#" class="block text-white hover:bg-indigo-700 px-3 py-2 rounded">Services</a>
      <div class="pl-4 space-y-1">
        <a href="#" class="block text-white hover:bg-indigo-700">Web Development</a>
        <a href="#" class="block text-white hover:bg-indigo-700">App Development</a>
        <a href="#" class="block text-white hover:bg-indigo-700">SEO Services</a>
      </div>
    </div>
    <a href="#" class="block text-white hover:bg-indigo-700 px-3 py-2 rounded">About</a>
    <a href="#" class="block text-white hover:bg-indigo-700 px-3 py-2 rounded">Contact</a>
  </div>
</nav>
```

### Responsive Navbar with Search and Button

<figure><img src="../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

```html
<nav class="bg-gray-800 p-4">
  <div class="container mx-auto flex justify-between items-center">
    <a href="#" class="text-white text-lg font-semibold">Brand</a>
    
    <button
      class="text-white md:hidden"
      onclick="document.getElementById('mobile-menu').classList.toggle('hidden')"
    >
      <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
      </svg>
    </button>

    <!-- Desktop Links and Search -->
    <div class="hidden md:flex items-center space-x-4">
      <a href="#" class="text-gray-300 hover:text-white">Home</a>
      <a href="#" class="text-gray-300 hover:text-white">About</a>
      <a href="#" class="text-gray-300 hover:text-white">Services</a>
      <input
        type="text"
        placeholder="Search"
        class="hidden lg:block px-3 py-1 rounded-lg border border-gray-700 bg-gray-700 text-gray-200 focus:outline-none focus:ring focus:ring-gray-600"
      />
      <a href="#" class="bg-blue-600 text-white px-3 py-2 rounded-lg hover:bg-blue-500">Sign Up</a>
    </div>
  </div>
  
  <!-- Mobile Menu -->
  <div id="mobile-menu" class="hidden md:hidden bg-gray-800 space-y-2 p-4">
    <a href="#" class="block text-gray-300 hover:text-white">Home</a>
    <a href="#" class="block text-gray-300 hover:text-white">About</a>
    <a href="#" class="block text-gray-300 hover:text-white">Services</a>
    <input
      type="text"
      placeholder="Search"
      class="w-full px-3 py-1 rounded-lg border border-gray-700 bg-gray-700 text-gray-200 focus:outline-none focus:ring focus:ring-gray-600"
    />
    <a href="#" class="block bg-blue-600 text-center text-white px-3 py-2 rounded-lg hover:bg-blue-500">Sign Up</a>
  </div>
</nav>
```

