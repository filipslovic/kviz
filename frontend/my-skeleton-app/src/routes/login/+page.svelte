<div class="min-h-screen flex flex-col justify-center items-center bg-gradient-to-br from-red-200 via-orange-200 to-yellow-200">

    <header class="bg-white shadow-md w-full z-10">
        <div class="container mx-auto px-4">
            <nav class="flex justify-between items-center py-4">
                <div class="flex items-center">
                    <a href="+page.svelte" class="relative">
                        <img src="/catLogotip.png" alt="Logo" class="h-16 w-auto mr-4 transition-transform duration-200 transform hover:scale-110">
                    </a>
                    <a href="+page.svelte" class="mr-4 text-2xl font-bold text-black transition-colors transition-transform duration-200 hover:text-blue-500 hover:scale-105">Play Game</a>
                    <a href="+page.svelte" class="mr-4 text-2xl font-bold text-black transition-colors transition-transform duration-200 hover:text-blue-500 hover:scale-105">Create Question</a>
                    <a href="+page.svelte" class="mr-4 text-2xl font-bold text-black transition-colors transition-transform duration-200 hover:text-blue-500 hover:scale-105">Status</a>
                    <a href="+page.svelte" class="mr-4 text-2xl font-bold text-black transition-colors transition-transform duration-200 hover:text-blue-500 hover:scale-105">Records</a>
                </div>
                <div class="flex items-center">
                    <a href="login" class="mr-4 text-2xl font-bold text-black transition-colors transition-transform duration-200 hover:text-blue-500 hover:scale-105">Login</a>
                    <a href="register" class="text-2xl font-bold text-black transition-colors transition-transform duration-200 hover:text-blue-500 hover:scale-105">Register</a>
                </div>
            </nav>
        </div>
    </header>

    <div class="min-h-screen flex justify-center items-center">
        <div class="absolute inset-0 bg-black bg-opacity-0 backdrop-filter backdrop-blur-sm flex justify-center items-center">
            <form class="bg-transparent border bg-white shadow-md rounded-xl px-10 py-12 mb-8">
                <h4 class="text-center text-3xl font-bold mb-6 text-black">Login</h4>
                <div class="mb-6">
                    <label for="exampleInputEmail1" class="block text-gray-700 text-lg font-bold mb-2">Email address</label>
                    <input type="email" class="shadow appearance-none border rounded w-full py-3 px-4 text-lg text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="exampleInputEmail1" aria-describedby="emailHelp">
                </div>
                <div class="mb-6">
                    <label for="exampleInputPassword1" class="block text-gray-700 text-lg font-bold mb-2">Password</label>
                    <input type="password" class="shadow appearance-none border rounded w-full py-3 px-4 text-lg text-gray-700 mb-3 leading-tight focus:outline-none focus:shadow-outline" id="exampleInputPassword1">
                    <p class="text-gray-600 text-sm italic">Nemate nalog? <a href="register" class="text-blue-500">registrujte se!</a></p>
                </div>
                <button type="submit" class="bg-primary-siva hover:bg-blue-700 text-white font-bold py-3 px-6 rounded focus:outline-none focus:shadow-outline">Login</button>
            </form>
        </div>
    </div>

</div>
