# Array-DS
Hackerrank solution 1

class Result {
    /*
     * Complete the 'reverseArray' function below.
     *
     * The function is expected to return an INTEGER_ARRAY.
     * The function accepts INTEGER_ARRAY a as parameter.
     */
    public static List<Integer> reverseArray(List<Integer> a) {
    // Write your code here
    ArrayList<Integer> lists= new ArrayList<Integer>();
    for(int i=a.size()-1;i>=0;i--)
    {
        lists.add(a.get(i));
       // Collections.reverse(lists);
    }
    return lists;
    }
}
