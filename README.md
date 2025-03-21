# Payroll_calculations-types
Types and its discription 

# Types of Pay-Roll information.



| No.| Questions                                                                                                                                                                   |
| ---| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|    | **concepts**                                                                                                                                                          |                                                                                                                                                                    
| 1  | [KRA-KPI'S](#)                                                                                                                                                           |
| 2  | [Payment-of-Gratuity](#)                                                                                                                                                 |
| 3  | [PF-Policies](#)                                                                                                                                                         |
| 4  | [Payroll-calculations](#)                                                                                                                                                |
| 5   |[Payroll-slabs](#)                                                                                                                                                       |


| 1  | [KRA KPI'S](#) 

![](./inputfoder/image1.png)


| 2 | [payment-of-Gratuity]

![](./inputfolder/image1.png)









1.  ### What is VueJS?
    **Vue.js** is an open-source, progressive Javascript framework for building user interfaces that aim to be incrementally adoptable. The core library of VueJS is focused on the `view layer` only, and is easy to pick up and integrate with other libraries or existing projects.

    **[⬆ Back to Top](#table-of-contents)**

2.  ### What are the major features of VueJS?
    Below are the some of major features available with VueJS
    1. **Virtual DOM:** It uses virtual DOM similar to other existing frameworks such as ReactJS, Ember etc. Virtual DOM is a light-weight in-memory tree representation of the original HTML DOM and updated without affecting the original DOM.
    2. **Components:** Used to create reusable custom elements in VueJS applications.
    3. **Templates:** VueJS provides HTML based templates that bind the DOM with the Vue instance data
    4. **Routing:** Navigation between pages is achieved through vue-router
    5. **Light weight:** VueJS is light weight library compared to other frameworks.

    **[⬆ Back to Top](#table-of-contents)**




     4. **Destruction (Teardown):**
        Destruction hooks allow you to perform actions when your component is destroyed, such as cleanup or analytics sending.
        1. beforeDestroy:
        `beforeDestroy` is fired right before teardown. If you need to cleanup events or reactive subscriptions, beforeDestroy would probably be the time to do it. Your component will still be fully present and functional.
        ```javascript
        new Vue ({
          data() {
            return {
              message: 'Welcome VueJS developers'
            }
          },

          beforeDestroy: function() {
            this.message = null
            delete this.message
          }
        })
        ```
        2. destroyed:
        This hooks is called after your component has been destroyed, its directives have been unbound and its event listeners have been removed.
        ```javascript
        new Vue ({
            destroyed: function() {
              console.log(this) // Nothing to show here
            }
          })
        ```

    **[⬆ Back to Top](#table-of-contents)**


