## Fast-forwarding
---

### ref1

* Fast forwarding moves the currently checked out commit to one that was added later, replaying all commits in between in the order which they happened.

* To fast-forward your currently checked out commit, you can right click on the branch with newer commits, 
and select the Fast-Forward option from the menu.


### ref2

* Merge 메시지에서 'Fast-forward'가 보이는가? 
* Merge할 브랜치가 가리키고 있던 커밋이 현 브랜치가 가리키는 것보다 '앞으로 진행한' 커밋이기 때문에 master 브랜치 포인터는 최신 커밋으로 이동한다.
* 이런 Merge 방식을 'Fast forward'라고 부른다. 
* 다시 말해서 A 브랜치에서 다른 B 브랜치를 Merge할 때 B가 A 이후의 커밋을 가리키고 있으면 그저 A가 B의 커밋을 가리키게 할 뿐이다.


### reference
---

[1] <https://support.gitkraken.com/working-with-repositories/pushing-and-pulling/>
[2] <https://git-scm.com/book/ko/v1/Git-%EB%B8%8C%EB%9E%9C%EC%B9%98-%EB%B8%8C%EB%9E%9C%EC%B9%98%EC%99%80-Merge%EC%9D%98-%EA%B8%B0%EC%B4%88>


