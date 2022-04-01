#Q1
/* Any Element With Class Title */
.title {
}

/* element with id=nav */
 #nav {
 }

/*any div element */
div {
}

/* any h2 element */
h2 {
}

#Q2
 External style! 
   <link rel="stylesheet" href="css/file.css" /> 

Internal style
<style>
p {
  color: red;
}
</style>

Inline style 
 <!-- <p style="color: blue;">This Is Our Paragraph  </p> -->

#Q5
/*  Valid  */
._user-name {
}

/* Valid */
.-user-name {
}

/*  Valid  */
.-user-name {
}

/* Not Valid  */
.1user-name {
}

/* Not Valid  */
.@user-name {
}

/* Not Valid  */
.user@name {
}

/*  Valid  */
._user10name {
}

/*  Valid */
.u {
}

#Q6
/* bad */
.USERNAME {
}

/* bad */
.UserName {
}

/* good */
.user-name {
}

/* bad */
.userName {
}

/* bad*/
.usernameprofile {
}