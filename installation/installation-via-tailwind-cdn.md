# Installation via Tailwind CDN

## Tailwind CSS Project setup using a CDN (Content Delivery Network)

{% hint style="warning" %}
The Play CDN is designed for development purposes only and is not the best choice for production.
{% endhint %}

{% hint style="info" %}
For production, you can use other options like Tailwind CLI, Using PostCSS which we will see later.
{% endhint %}

### ✅ Steps to follow to complete Tailwind CSS Setup Successfully

1. Start by creating a new HTML file or open an existing one where you want to use Tailwind CSS.

<figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

2. Add an HTML boilerplate code to that HTML file

{% code title="index.html" lineNumbers="true" fullWidth="false" %}
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tailwind CSS CDN Setup</title>
  </head>
  <body>
    <!-- OUR HTML CODE -->
  </body>
</html>
```
{% endcode %}

3. Open the Tailwind CSS website ([https://tailwindcss.com/](https://tailwindcss.com/)) in your browser and navigate to the "Installation" section.
4. In the installation section, you will find the option to use the CDN. Copy the CDN link provided under the "Using a CDN" heading. The link should look something like this:

```javascript
<script src="https://cdn.tailwindcss.com"></script>
```

5. Paste the copied script tag into the `<head>` section of your HTML file. It should look like this

{% code title="index.html" lineNumbers="true" %}
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tailwind CSS CDN Setup</title>
    <!-- TAILWIND CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
  </head>
  <body>
    <!-- OUR HTML CODE -->
  </body>
</html>
```
{% endcode %}

6. The setup process is done 😎, Now just use tailwind css classes inside the `index.html`
7. Here is an example:

{% code title="index.html" lineNumbers="true" %}
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tailwind CSS CDN Setup</title>
    <!-- TAILWIND CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
  </head>
  <body>
    <!-- OUR HTML CODE -->
    <div class="flex justify-center items-center h-screen">
      <div
        class="bg-gray-800 text-white font-bold rounded-lg border shadow-lg p-10"
      >
        Tailwind CSS CDN Setup
      </div>
    </div>
  </body>
</html>
```
{% endcode %}

Output:

<figure><img src="../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

OR simply clone this GitHub repository:

{% embed url="https://github.com/prahladinala/simple-tailwind-cdn-starter" %}

### For a more detailed article refer to the following:

{% embed url="https://blogs.prahladinala.in/series/tailwind" %}
