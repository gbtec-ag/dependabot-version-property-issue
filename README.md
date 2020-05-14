# commit history and behavior

## initial commit containing a pom with 5 dependencies (after commit 6db4b36)
* 5 dependencies available in pom (1 dependency is managed). 
* 5 dependencies were checked.
* 4 PRs created.

## define 'guava' version as property (after commit 42e55cb)
* 5 dependencies available in pom (1 dependency is managed).
* 5 dependencies were checked.
* 4 PRs still open.

## rename 'spring-boot' version property to 'project.dependency.spring-boot.version' (after commit 797dcef)
* 5 dependencies available in pom (1 dependency is managed).
* 4 dependencies were checked.
* 1 dependency ('spring-boot-dependencies') is not checked anymore.
* 3 PRs still open.
* 1 PR closed.
* Got two emails.
    * One email contained 'Looks like org.springframework.boot:spring-boot-dependencies is no longer a dependency, so this is no longer needed.'
    * One email contained 'Closed #1.'

## rename 'spring-boot' version property back to 'spring-boot.version' (after commit 542df3f)
* 5 dependencies available in pom (1 dependency is managed).
* 5 dependencies were checked.
* 1 dependency ('spring-boot-dependencies') is checked again but Dependabot believes that a PR is already available (obviously the closed one).

## check a second time after renaming 'spring-boot' version property back to 'spring-boot.version' (after commit 54904f2)
* 5 dependencies available in pom (1 dependency is managed).
* 5 dependencies were checked.
* 1 dependency ('spring-boot-dependencies') is checked again but Dependabot believes that a PR is already available (obviously the closed one).

## rename 'spring-boot' version property back to 'spring.version' (after commit 97c47f9)
* 5 dependencies available in pom (1 dependency is managed).
* 5 dependencies were checked.
* 1 dependency ('spring-boot-dependencies') is checked again but Dependabot believes that a PR is already available (obviously the closed one).

## rename 'guava' version property to 'a.b.c.d.version' (after commit 10a1383)
* 5 dependencies available in pom (1 dependency is managed).
* 5 dependencies were checked.
* 1 dependency ('spring-boot-dependencies') is checked again but Dependabot believes that a PR is already available (obviously the closed one).
