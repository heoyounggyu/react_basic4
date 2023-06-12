
    

![image](https://github.com/heoyounggyu/react_basic4/assets/129017041/51609ccd-3439-45a5-b645-1b7bfd023e4a)

    npm i json-server
# db.json 파일 만들기
![image](https://github.com/heoyounggyu/react_basic4/assets/129017041/f1c0ef4a-9f85-4701-b743-f001075b04d9)

# db.json파일은  root에 만들어야 한다
![image](https://github.com/heoyounggyu/react_basic4/assets/129017041/a72c759a-35a7-45ae-8066-1d6c5f9ae82f)

# db.json 실행하기

![image](https://github.com/heoyounggyu/react_basic4/assets/129017041/48c9d2ff-33e0-4fd2-b77d-e8fdf65c207f)


# 위와 같이 실행하면 port를 3000을 사용하기 때문에 react와 중복이 되어버린다
그래서 prot를 변경해야 한다

    json-server --watch db.json
# 아래를 실행이 안된다면 아래를 적용한다
     npx json-server --watch db.json
