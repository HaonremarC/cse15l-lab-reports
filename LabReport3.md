PART 1
1. Code for failure-inducing output:
   `@Test
  public void testReversedFailure(){
    int[] arr = {1,2,3,4,5};
    int[] expected = {5,4,3,2,1};
    ArrayExamples.reverseInPlace(arr);
    assertArrayEquals(expected, arr);
  }`

2. code for success-inducing output:
   `@Test
  public void testReversedSuccess(){
    int[] arr = {0,1,0};
    int[] expected = {0,1,0};
    ArrayExamples.reverseInPlace(arr);
    assertArrayEquals(expected, arr);
  }`

3. 
