Name: Devlin Junker

Functions

main
    reads command line arguments and decides where to read the input from (command line or text file). Reads a test case input then calls run_test_case

run_test_case
    determines which algorithm to run based on the command line input and calls the appropriate function, after it runs collects the details and calls print_case_details with them.

brute_force
    runs the brute force algorithm stepping through the list, checking all of the following numbers for inversions

divide
    divides the list into sublists and counts the number of inversions in the sublist, then counts the number of inversions across the lists

merge_count
    divides the list into sublists and calls itself recursively on them, then calls the merge function to  merges them together

merge
    merges the two sublists and counts the number of inversions across the merging lists

print_case_details
    prints the details from each test case including the input list, number of elements in the list, number of inversions in the list and the time it took to count the inversions

