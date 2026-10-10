# AWS Interview Answers

## AWS Fundamentals

### Q1. What is AWS?

#### 1. English Definition

**AWS (Amazon Web Services) is a cloud computing platform that provides services like servers, storage, databases, and networking over the internet. It helps developers deploy and scale applications without maintaining physical servers.**

#### 2. Hindi Definition

AWS (Amazon Web Services) Amazon ka ek cloud platform hai, jo internet ke through server, storage, database aur networking jaisi services provide karta hai. Iski madad se developers apni applications ko deploy aur scale kar sakte hain, bina khud physical servers maintain kiye.

#### 3. Hinglish Explanation

Maan lo tumne MERN Stack mein ek e-commerce website banayi hai:

- React.js — Frontend
- Node.js + Express.js — Backend
- MongoDB — Database

Ab tum chahte ho ki website internet par live ho aur users use access kar sakein. Iske liye backend run karne ke liye server, images ke liye storage aur product/user data ke liye database chahiye.

AWS tumhe cloud par ye resources use karne deta hai. Tumhe apna physical server khareedkar maintain karne ki zarurat nahi hoti.

**Simple words mein:** AWS ek cloud platform hai jahan tum apni application deploy aur run karne ke liye required infrastructure use kar sakte ho.

#### 4. Practical Example — MERN Application

Maan lo tum apni e-commerce application AWS par deploy karte ho:

```text
User / Browser
     |
     v
React.js Frontend
     |
     v
Amazon EC2
(Node.js + Express Backend)
     |                 |
     v                 v
  MongoDB           Amazon S3
(User/Product Data) (Images/Files)
```

**Working flow:**
1. User product search karta hai.
2. React frontend backend ko API request bhejta hai.
3. EC2 par running Node.js backend request process karta hai.
4. Backend MongoDB se product details fetch karta hai.
5. Product images S3 se serve ho sakti hain.
6. Backend response frontend ko bhej deta hai.

**Note:** MongoDB ke liye MongoDB Atlas ya self-managed MongoDB use kar sakte ho. Amazon DocumentDB ek MongoDB-compatible managed database alternative hai.

#### 5. Practical Command

AWS CLI se configured AWS identity check karne ke liye:

```bash
aws sts get-caller-identity
```

Ye command configured AWS credentials se associated AWS account aur identity ki details return karti hai.

#### 6. Summary Table

| Topic | Easy Meaning |
|---|---|
| AWS | Amazon ka cloud computing platform |
| EC2 | Virtual server par application run karna |
| S3 | Images aur files store karna |
| RDS | Relational database service |
| IAM | Users aur permissions manage karna |
| Main purpose | Applications ko deploy, run aur scale karna |

**Yaad rakhne ki trick:** AWS ek platform hai, aur EC2, S3 aur IAM uski alag-alag services hain.
