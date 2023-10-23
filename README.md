In this project, let's build a **Password Manager** by applying the concepts we have learned till now.

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/passowrd-manager-output-v0.gif" alt="password manager" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Design Files

<details>
<summary>Click to view</summary>

- [Extra Small (Size < 576px) and Small (Size >= 576px) - No Passwords View](https://assets.ccbp.in/frontend/content/react-js/password-manager-no-passwords-sm-output-v2.png)
- [Extra Small (Size < 576px) and Small (Size >= 576px) - Masked Passwords View](https://assets.ccbp.in/frontend/content/react-js/password-manager-masked-passwords-sm-output-v2.png)
- [Extra Small (Size < 576px) and Small (Size >= 576px) - Show Passwords View](https://assets.ccbp.in/frontend/content/react-js/password-manager-sm-output-v2.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - No Passwords View](https://assets.ccbp.in/frontend/content/react-js/password-manager-no-passwords-lg-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Masked Passwords View](https://assets.ccbp.in/frontend/content/react-js/password-manager-masked-passwords-lg-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Show Passwords View](https://assets.ccbp.in/frontend/content/react-js/password-manager-lg-output.png)

</details>

### Set Up Instructions

<details>
<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>

### Completion Instructions

<details>
<summary>Functionality to be added</summary>
<br/>

The app must have the following functionalities

- Initially, the website input, username input, and password input should be empty and [No Passwords View](https://assets.ccbp.in/frontend/content/react-js/password-manager-no-passwords-lg-output.png) should be displayed
- When non-empty values are provided for the website, username, and password and the **Add** button is clicked,
  - A new password item should be added to the list of passwords
  - The passwords count should be incremented by one
  - The **stars image** should be displayed in the password items instead of the passwords
  - The value of the input fields for website, username, and password should be updated to their initial values
  - When the **Show Password** is checked, then the password should be displayed instead of the **stars image**
- When a non-empty value is provided in the search input field, then password items whose website is matched with the search input value irrespective of the case should be displayed
- When a non-empty value is provided in the search input field, and if the website of any password item does not match the value given in the search input, then [No Passwords View](https://assets.ccbp.in/frontend/content/react-js/password-manager-no-passwords-lg-output.png) should be displayed
- When the delete button of a password item is clicked,
  - The respective password item should be deleted from the list of passwords
  - The passwords count should be decremented by one
- When all password items are deleted, then [No Passwords View](https://assets.ccbp.in/frontend/content/react-js/password-manager-no-passwords-lg-output.png) should be displayed
</details>

### Important Note

<details>
<summary>Click to view</summary>

<br/>

**The following instructions are required for the tests to pass**

- HTML input element for website should have the placeholder as **Enter Website**
- HTML input element for username should have the placeholder as **Enter Username**
- HTML input element for password should have the placeholder as **Enter Password**
- The delete button for each password item should have the data-testid as **delete**
</details>

### Resources

<details>
<summary>Image URLs</summary>

- [https://assets.ccbp.in/frontend/react-js/password-manager-logo-img.png](https://assets.ccbp.in/frontend/react-js/password-manager-logo-img.png) alt should be **app logo**
- [https://assets.ccbp.in/frontend/react-js/password-manager-sm-img.png](https://assets.ccbp.in/frontend/react-js/password-manager-sm-img.png) alt should be **password manager**
- [https://assets.ccbp.in/frontend/react-js/password-manager-lg-img.png](https://assets.ccbp.in/frontend/react-js/password-manager-lg-img.png) alt should be **password manager**
- [https://assets.ccbp.in/frontend/react-js/password-manager-website-img.png](https://assets.ccbp.in/frontend/react-js/password-manager-website-img.png) alt should be **website**
- [https://assets.ccbp.in/frontend/react-js/password-manager-username-img.png](https://assets.ccbp.in/frontend/react-js/password-manager-username-img.png) alt should be **username**
- [https://assets.ccbp.in/frontend/react-js/password-manager-password-img.png](https://assets.ccbp.in/frontend/react-js/password-manager-password-img.png) alt should be **password**
- [https://assets.ccbp.in/frontend/react-js/password-manager-search-img.png](https://assets.ccbp.in/frontend/react-js/password-manager-search-img.png) alt should be **search**
- [https://assets.ccbp.in/frontend/react-js/no-passwords-img.png](https://assets.ccbp.in/frontend/react-js/no-passwords-img.png) alt should be **no passwords**
- [https://assets.ccbp.in/frontend/react-js/password-manager-stars-img.png](https://assets.ccbp.in/frontend/react-js/password-manager-stars-img.png) alt should be **stars**
- [https://assets.ccbp.in/frontend/react-js/password-manager-delete-img.png](https://assets.ccbp.in/frontend/react-js/password-manager-delete-img.png) alt should be **delete**
</details>

<details>
<summary>Colors</summary>

<br/>

<div style="background-color: #9ba9eb; width: 150px; padding: 10px; color: black">Hex: #9ba9eb</div>
<div style="background-color: #c3caea; width: 150px; padding: 10px; color: black">Hex: #c3caea</div>
<div style="background-color: #5763a5; width: 150px; padding: 10px; color: black">Hex: #5763a5</div>
<div style="background-color: #f8fafc; width: 150px; padding: 10px; color: black">Hex: #f8fafc</div>
<div style="background-color: #454f84; width: 150px; padding: 10px; color: white">Hex: #454f84</div>
<div style="background-color: #0b69ff; width: 150px; padding: 10px; color: black">Hex: #0b69ff</div>
<div style="background-color: #94a3b8; width: 150px; padding: 10px; color: black">Hex: #94a3b8</div>
<div style="background-color: #b6c3ca; width: 150px; padding: 10px; color: black">Hex: #b6c3ca</div>
<div style="background-color: #7683cb; width: 150px; padding: 10px; color: black">Hex: #7683cb</div>
<div style="background-color: #f59e0b; width: 150px; padding: 10px; color: black">Hex: #f59e0b</div>
<div style="background-color: #10b981; width: 150px; padding: 10px; color: black">Hex: #10b981</div>
<div style="background-color: #f97316; width: 150px; padding: 10px; color: black">Hex: #f97316</div>
<div style="background-color: #14b8a6; width: 150px; padding: 10px; color: black">Hex: #14b8a6</div>
<div style="background-color: #b91c1c; width: 150px; padding: 10px; color: black">Hex: #b91c1c</div>
<div style="background-color: #ffffff; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>
<div style="background-color: #0ea5e9; width: 150px; padding: 10px; color: black">Hex: #0ea5e9</div>
<div style="background-color: #64748b; width: 150px; padding: 10px; color: white">Hex: #64748b</div>

</details>

<details>
<summary>Font-families</summary>

- Roboto

</details>

> ### _Things to Keep in Mind_
>
> - All components you implement should go in the `src/components` directory.
> - Don't change the component folder names as those are the files being imported into the tests.
> - **Do not remove the pre-filled code**
> - Want to quickly review some of the concepts you’ve been learning? Take a look at the Cheat Sheets.


###_from here the correct code of App.js file is pasted_
import {Component} from 'react'

import {v4 as uuidv4} from 'uuid'

import './App.css'

// code implementing from here Ashfaq khan
// 4 test cases failed out of 34
const colorList = ['yellow', 'green', 'orange', 'brown', 'blue']

class App extends Component {
  state = {
    isTrue: false,
    latestList: [],
    website: '',
    username: '',
    password: '',
    isShow: false,
  }

  listenWebsite = e => {
    this.setState({website: e.target.value})
  }

  listenUsername = e => {
    this.setState({username: e.target.value})
  }

  listenPassword = e => {
    this.setState({password: e.target.value})
  }

  addContent = e => {
    e.preventDefault()
    const {username, website, password} = this.state
    const initial = website.slice(0, 1).toUpperCase()
    const classValue = colorList[Math.floor(Math.random() * 5)]
    const newValues = {
      id: uuidv4(),
      initialValue: initial,
      websiteName: website,
      userName: username,
      Password: password,
      classAdd: classValue,
    }
    this.setState(prevState => ({
      latestList: [...prevState.latestList, newValues],
      website: '',
      username: '',
      password: '',
      isTrue: true,
      searchInput: '',
    }))
  }

  showPassword = e => {
    if (e.target.checked) {
      this.setState({isShow: true})
    } else {
      this.setState({isShow: false})
    }
  }

  searchList = e => {
    this.setState({searchInput: e.target.value})
  }

  deleteItem = id => {
    const {latestList} = this.state
    const newList = latestList.filter(eachValue => eachValue.id !== id)
    const caseOf = newList.length !== 0
    this.setState({latestList: newList, isTrue: caseOf})
  }

  render() {
    const {
      website,
      username,
      password,
      latestList,
      isShow,
      searchInput,
    } = this.state
    let {isTrue} = this.state
    const newList = latestList.filter(eachValue =>
      eachValue.websiteName.toLowerCase().includes(searchInput.toLowerCase()),
    )
    if (newList.length === 0) {
      isTrue = false
    } else {
      isTrue = true
    }
    return (
      <div className="main-container">
        <img
          src="https://assets.ccbp.in/frontend/react-js/password-manager-logo-img.png"
          className="app-logo"
          alt="app logo"
        />
        <div className="sub-div1">
          <img
            src="https://assets.ccbp.in/frontend/react-js/password-manager-sm-img.png"
            className="sub-div1-image2"
            alt="password manager"
          />
          <form className="add-details" onSubmit={this.addContent}>
            <h1 className="detail-heading">Add New Password</h1>
            <div className="input-holder">
              <img
                src="https://assets.ccbp.in/frontend/react-js/password-manager-website-img.png"
                className="input-image"
                alt="website"
              />
              <input
                type="text"
                className="input-element"
                placeholder="Enter Website"
                onChange={this.listenWebsite}
                value={website}
              />
            </div>

            <div className="input-holder">
              <img
                src="https://assets.ccbp.in/frontend/react-js/password-manager-username-img.png"
                className="input-image"
                alt="username"
              />
              <input
                type="text"
                className="input-element"
                placeholder="Enter Username"
                onChange={this.listenUsername}
                value={username}
              />
            </div>
            <div className="input-holder">
              <img
                src="https://assets.ccbp.in/frontend/react-js/password-manager-password-img.png"
                className="input-image"
                alt="password"
              />
              <input
                type="password"
                className="input-element"
                placeholder="Enter Password"
                onChange={this.listenPassword}
                value={password}
              />
            </div>
            <button type="submit" className="add-btn">
              Add
            </button>
          </form>
          <img
            src="https://assets.ccbp.in/frontend/react-js/password-manager-lg-img.png"
            className="sub-div1-image1"
            alt="password manager"
          />
        </div>
        <div className="sub-div2">
          <div className="first-div">
            <div className="your-password">
              <h1 className="heading-name">Your Passwords</h1>
              <p className="colored-text">{newList.length}</p>
            </div>
            <div className="search-holder">
              <img
                src="https://assets.ccbp.in/frontend/react-js/password-manager-search-img.png"
                className="input-image"
                alt="search"
              />
              <input
                type="search"
                className="input-element"
                placeholder="Search"
                onChange={this.searchList}
                value={searchInput}
              />
            </div>
          </div>
          <hr />
          <div className="show-passwords">
            <input
              type="checkbox"
              className="check-box"
              id="check"
              onChange={this.showPassword}
            />
            <label htmlFor="check" className="label-password">
              Show Passwords
            </label>
          </div>
          {!isTrue && (
            <div className="empty-state">
              <img
                src="https://assets.ccbp.in/frontend/react-js/no-passwords-img.png"
                className="empty-image"
                alt="no passwords"
              />
              <p className="no-passwords">No Passwords</p>
            </div>
          )}
          {isTrue && (
            <ul className="result-container">
              {newList.map(eachValue => (
                <li className="item-list" id={eachValue.id} key={eachValue.id}>
                  <p className={`initial ${eachValue.classAdd}`}>
                    {eachValue.initialValue}
                  </p>
                  <div className="list-content">
                    <p className="website">{eachValue.websiteName}</p>
                    <p className="website">{eachValue.userName}</p>
                    {!isShow && (
                      <img
                        src="https://assets.ccbp.in/frontend/react-js/password-manager-stars-img.png"
                        className="stars-image"
                        alt="stars"
                      />
                    )}
                    {isShow && <p className="website">{eachValue.Password}</p>}
                  </div>
                  <button
                    type="button"
                    className="del-btn"
                    data-testid="delete"  // here the update is done and all the 38/38 cases have passed. earlier only 34 cases were passed, because i didnt add this attribute to the delete button.
                    onClick={() => this.deleteItem(eachValue.id)}
                  >
                    <img
                      src="https://assets.ccbp.in/frontend/react-js/password-manager-delete-img.png"
                      className="del-image"
                      alt="delete"
                    />
                  </button>
                </li>
              ))}
            </ul>
          )}
        </div>
      </div>
    )
  }
}

export default App

Project URL: https://ashupasswordapp.ccbp.tech
