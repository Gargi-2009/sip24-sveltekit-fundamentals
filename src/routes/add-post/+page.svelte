<header class="bg-white py-4 shadow-md sticky top-0 z-10">
    <div class ="container mx-auto px-4 flex justify-between items-center">
        <h1 class="text-2xl font-bold font-['Comic_Sans_MS']"> craftlab </h1>
        <a href="/" class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">Home</a>
    </div>
        </header>

        <form class="container mx-auto p-5">
            <div>
            <input type="file" />
            </div>
            <div>
                <label for="dropzone" class="mb-3 flex flex-col items-centre justif-centre w-full h-64 border-gray-300 ">
                <div class="flex flex-col items-centre justify-centre pt-5 pb-6">
                <svg class="w-8 h-8 mb-4 text-gray-500" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none"></svg>
                 <p class="text-sm text-gray-500 font-semibold">Click to upload</p>   
                </div>
                
            <input id="dropzone" type="file" accept="image/png,image/jpeg" class="hidden" required>
                
        </label>
        </div>    
        <div>
                <label>Username</label>
             <input type="text" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg block w-full p-2.5"/>
                </div>
        </form>
