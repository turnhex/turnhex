
### **index.html** (with Tailwind CSS):

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="TurnHex - A cybersecurity and hacking explorer">
    <title>TurnHex - Explore Cybersecurity</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-900 text-white">

    <!-- Header Section -->
    <header class="flex items-center justify-between p-6 bg-gray-800">
        <img src="your-logo.png" alt="TurnHex Logo" class="h-12">
        <h1 class="text-4xl font-bold">TurnHex</h1>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto p-8">
        <section class="text-center">
            <h2 class="text-3xl font-semibold mb-4">Welcome to TurnHex</h2>
            <p class="text-xl mb-6">Exploring the world of hacking and cybersecurity</p>
            <button class="bg-blue-500 text-white px-6 py-3 rounded-lg hover:bg-blue-400 transition">Join the Community</button>
        </section>

        <!-- Features Section -->
        <section class="mt-12">
            <h3 class="text-2xl font-semibold mb-4">What you'll find here:</h3>
            <ul class="list-disc pl-6 space-y-3">
                <li>💻 Hacking tutorials and techniques</li>
                <li>🔒 Insights into cybersecurity vulnerabilities</li>
                <li>⚡ Real-world exploitation examples</li>
            </ul>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-center py-6 mt-12">
        <p>Connect with me: <a href="mailto:turnhex@cybermail.com" class="text-blue-400">turnhex@cybermail.com</a></p>
        <p>&copy; 2024 TurnHex. All rights reserved.</p>
    </footer>

</body>
</html>
