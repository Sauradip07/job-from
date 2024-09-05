
# Multi-Page Form with Tabs

This project implements a multi-page form with three steps: **Requisition Details**, **Job Details**, and **Interview Settings**. Users can navigate between the tabs while maintaining form state, and the draft card dynamically updates in real-time based on the user input.

## Features

- **Multi-Page Form with Validation**: Users can navigate between three tabs (Requisition Details, Job Details, Interview Settings), but only after successfully submitting the form in the current step.
- **Form Validation**: Each form step must be filled without errors before moving to the next step. If there are validation errors, the form will prevent proceeding to the next tab.
- **Tab Navigation**: Users can only move between steps using **Next** and **Previous** buttons. Clicking **Next** moves to the next step only if the form is error-free, and clicking **Previous** retains already filled form values.
- **Real-Time Draft Card**: A draft card updates in real-time based on the user's input, reflecting the current form state.

## Features Requests (Implemented)

- **Real-Time Draft Card**: Values in the draft card update dynamically based on what the user enters into the forms.
- **Form Navigation**: Users can only move between tabs using buttons inside the forms. The next tab can only be accessed after filling out the current form without any errors. Moving to the previous step retains the form values.

## Bug Fixes

- **Form Not Proceeding to Next Step**: Fixed the issue where, in the Job Details form, the user couldn't proceed to the next step despite having no errors.
- **Missing Validations**: Added missing validations to the Interview Settings form.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
