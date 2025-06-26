<html>
<html lang="en">
<head>

    <title>URL Shortener</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    
</head>
<body class="min-h-screen bg-gradient-to-br from-purple-600 to-indigo-800 flex items-center justify-center p-4">
    <div class="bg-white p-8 rounded-2xl shadow-xl max-w-2xl w-full">
        <h1 class="text-3xl font-bold text-center text-gray-800 mb-6">URL Shortener</h1>
        <div class="mb-8 p-6 bg-gray-50 rounded-xl shadow-inner">
            <h2 class="text-2xl font-semibold text-gray-700 mb-4">Shorten Your URL</h2>
            <input type="url" placeholder="Original URL" class="shadow border rounded-lg w-full py-3 px-4 mb-4">
            <input type="text" placeholder="Custom Shortcode (Optional)" class="shadow border rounded-lg w-full py-3 px-4 mb-4">
            <input type="number" placeholder="Validity (minutes)" class="shadow border rounded-lg w-full py-3 px-4 mb-4">
            <button class="w-full bg-purple-700 text-white py-3 rounded-lg">Shorten URL</button>
        </div>
        <div class="mt-6 p-4 bg-purple-100 rounded-lg">
            <span class="text-purple-900">Shortened URL will appear here</span>
            <button class="bg-purple-500 text-white py-2 px-4 rounded-lg">Copy</button>
        </div>
    </div>
</body>
</html>
