<template>
    <div>
    <span class="isolate inline-flex rounded-md shadow-sm print:hidden">
                
                <button
                    type="button"
                    @click="reloadReport()"
                    class="relative -ml-px inline-flex items-center rounded-r-md border border-gray-300 bg-white p-0.5 pr-2 px-0 text-xs font-medium text-gray-700 hover:bg-gray-50 focus:z-10 focus:border-indigo-500 focus:outline-none focus:ring-1 focus:ring-indigo-500"
                >
                    <RefreshIcon class="ml-2 mr-2 h-5 w-5 text-gray-400" aria-hidden="true" />
                    Update&nbsp;Report
                </button>
                <button
                    type="button"
                    @click="openCloseToggle()"
                    class="relative -ml-px inline-flex items-center rounded-r-md border border-gray-300 bg-white p-0.5 pr-2 px-0 text-xs font-medium text-gray-700 hover:bg-gray-50 focus:z-10 focus:border-indigo-500 focus:outline-none focus:ring-1 focus:ring-indigo-500"
                >
                &nbsp;Open
                </button>
            </span>
        </div>

</template>
<script setup>
function reloadReport(){
    return alert('you hit print')
}
function openCloseToggle() {
   return alert ("open")
}


</script >