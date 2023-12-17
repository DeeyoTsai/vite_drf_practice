<template>
    <div class="max-w-7xl mx-auto grid grid-cols-2 gap-4">
        <div class="main-left">
            <div class="p-12 bg-white border border-gray-200 rounded-lg">
                <h1 class="text-2xl mb-6 font-bold">Sign up</h1>
            
                <div class="mb-6 text-gray-500">
                    請輸入工號、信箱與密碼註冊帳號!! <br>
                    已註冊帳號，密碼預設為工號末三碼。
                </div>
                
                <p class=" font-bold">
                    Already have an account? <RouterLink :to="{'name':'login'}" class="underline">Click here</RouterLink> to log in!
                </p>
            </div>
        </div>
        <div class="main-right">
            <div class="p-12 bg-white border border-gray-200 rounded-lg">
                <form class="space-y-6">

                    <div>
                        <label class=" font-bold">帳號:</label><br>
                        <input type="text" placeholder="請輸入工號" class=" w-full mt-2 py-4 px-6 border border-gray-200 rounded-lg">
                    </div>
                    <div>
                        <label class=" font-bold">e-mail:</label><br>
                        <input type="text" placeholder="請輸入email" class=" w-full mt-2 py-4 px-6 border border-gray-200 rounded-lg">
                    </div>
                    <div>
                        <label class=" font-bold">密碼:</label><br>
                        <input type="password" placeholder="請輸入密碼" class=" w-full mt-2 py-4 px-6 border border-gray-200 rounded-lg">
                    </div>
                    <div>
                        <label class=" font-bold">確認密碼:</label><br>
                        <input type="password" placeholder="請再次輸入密碼" class=" w-full mt-2 py-4 px-6 border border-gray-200 rounded-lg">
                    </div>
                    <div>
                        <button class="py-4 px-6 bg-purple-600 text-white rounded-lg">Sign up</button>
                    </div>
                        

                </form>
            </div>
        </div>
        
    </div>
        
        
</template>