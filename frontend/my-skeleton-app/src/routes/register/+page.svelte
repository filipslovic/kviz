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

    <div class="flex flex-col items-center mt-8">
        <div class="bg-black bg-opacity-0 backdrop-filter backdrop-blur-sm flex justify-center items-center">
            <form class="bg-transparent border bg-white shadow-md rounded-xl px-10 py-12 mb-8">
                <h4 class="text-center text-3xl font-bold mb-6 text-black">Register</h4>
                <div class="mb-6">
                    <label for="nickname" class="block text-gray-700 text-lg font-bold mb-2">Username</label>
                    <input type="username" class="shadow appearance-none border rounded w-full py-3 px-4 text-lg text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="exampleInputEmail1" aria-describedby="emailHelp">
                </div>

                <div class="mb-6">
                    <label for="" class="block text-gray-700 text-lg font-bold mb-2">Email address</label>
                    <input type="email" class="shadow appearance-none border rounded w-full py-3 px-4 text-lg text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="exampleInputEmail1" aria-describedby="emailHelp">
                </div>

                <div class="mb-6">
                    <label for="exampleInputPassword1" class="block text-gray-700 text-lg font-bold mb-2">Password</label>
                    <input type="password" class="shadow appearance-none border rounded w-full py-3 px-4 text-lg text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="exampleInputEmail1" aria-describedby="emailHelp">
                </div>

                <div class="mb-6">
                    <label for="exampleInputPassword2" class="block text-gray-700 text-lg font-bold mb-2">Confirm Password</label>
                    <input type="password" class="shadow appearance-none border rounded w-full py-3 px-4 text-lg text-gray-700 mb-3 leading-tight focus:outline-none focus:shadow-outline" id="exampleInputPassword1">
                    <p class="text-gray-600 text-sm italic">Imate nalog? <a href="login" class="text-blue-500">login</a></p>
                </div>
                <div style="text-align: center;">
                    <button type="submit" class="btn  bg-primary-siva transition-transform duration-200 hover:bg-gradient-to-br from-red-200 via-orange-200 to-yellow-200 text-white font-bold py-3 px-8 rounded-full focus:outline-none focus:shadow-outline hover:text-black ">Login</button>
                </div>
            </form>
        </div>
    </div>
</div>
