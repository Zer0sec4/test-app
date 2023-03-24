import Head from 'next/head';
import styles from '../styles/Home.module.css';
  

export default function Home() {
  return (
    <div className={styles.card}>
      <Head>
      <title>Create Next App</title>
        <link rel="icon" href="/favincon.png" />
      </Head>

      <font size="+3" style={{color: "black", backgroundColor: "orange", }}>Sign Up here to be like Mike!</font>


<form action="/send-data-here" method="post">
  <label for="first">First name:</label>
  <input type="text" id="first" name="first" />
  <label for="last">Last name:</label>
  <input type="text" id="last" name="last" />
  <button type="submit">Submit</button> 
  <label for="first">Email:</label>
  <input type="text" id="first" email="first" />
  <button type="submit">Submit</button>
  
</form>




<form action="/action_page.php">
  <label for="pswrd">Password:</label>
  <input
    type="password"
    id="pswrd"
    name="pswrd"
    pattern="[a-z0-9]{1,15}"
    title="Password should be digits (0 to 9) or alphabets (a to z)."
  />

  <button type="submit">Submit</button>
</form>

<a className={styles.return} href="/" >
return to front page
</a>





     
    </div>
  )
}
