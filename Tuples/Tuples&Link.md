<h1>Tuples
    <h3>Example:</h3> 
        tup=(0,1.5,(2,3,4),"ABC")
    <h3>Immutable:</h3> 
        only use funcs ex:tup=sorted((1,23,45,6)), tup=(45,23,6,1)
    <h3>Nesting:</h3> 
        tup = (1,2,("hello","world"),1.2) , tup[2][1]="hello"

<h1>List
    <h3>Example:</h3> L=[0,1.5,[2,3,4],"ABC"]
    <h3>Mmutable:</h3>
        L[0]=10 L=[10,1.5,[2,3,4],"ABC"] <b>
        L1=[1,2], L2=[3,4] then L1+L2 = [1,2,3,4]<b>
        L1.extend([5,6]) then L1=[1,2,5,6]<b>
        L1.append([5,6]) then L1=[1,2,[5,6]]<b>
    <h3>Nesting:</h3> 
        L1 = [1,2,["hello","world"],1.2] , L1[2][1]="hello"

<h1>Aliasing & Clone
    <h3>Aliasing</h3>
        A=[1,2,3,4]
        B=A then A[0]=B[0]=1
        if A=[5,6,7,8] then B[0]=5
    <h3>Clone</h3>
        A=[1,2,3,4]
        B=A[:] then A[0]=B[0]=1
        if A=[5,6,7,8] then B[0]=1, A[0]=5
