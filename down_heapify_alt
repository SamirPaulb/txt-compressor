 down_heapify(){
   let left = 2 * index + 1,
      right = 2 * index + 2,
      largest = index;
  const length = this.size();

  // console.log(this.heap[left], left, length, this.heap[right], right, length, this.heap[largest]);

  if (left < length && this.heap[left][0] > this.heap[largest][0]) {
      largest = left
  }
  if (right < length && this.heap[right][0] > this.heap[largest][0]) {
      largest = right
  }
  // swap
  if (largest !== index) {
      let tmp = this.heap[largest];
      this.heap[largest] = this.heap[index];
      this.heap[index] = tmp;
      this.down_heapify(largest)
  }
}
