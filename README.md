# -一 、归并排序法
   MergeSort(arr,l,r)
   对arr的[l,r]部分排序
   MergeSort(arr,l,r){ int mid=(l+r)/2;
   对arr[l,mid]进行排序 对arr[mid+1,r]进行排序
   将arr[l,mid]和arr[mid+1,r]合并
二、归并排序法的复杂度分析O（nlogn）
   一共logn层，每层总共是O（n）
