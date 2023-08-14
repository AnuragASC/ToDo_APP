# TODO APP

The ToDo App is a user-friendly Android application designed to simplify task management and help users stay organized. This app provides an intuitive interface for creating, editing, and deleting tasks, along with gesture-based interactions for a seamless experience. Built using modern Android technologies, including Jetpack Compose and RecyclerViewSwipeDecorator, the app delivers a smooth and efficient task management solution.

# FEATURES

1) Task Management Made Easy: Effortlessly create, edit, and delete tasks using intuitive gestures and interactions.

2) Sleek and Intuitive UI: The app features a modern and minimalistic user interface that focuses on clarity and simplicity.

3) Swipe Gestures: Utilize swipe gestures to perform actions such as editing and deleting tasks, enhancing efficiency.

4) Responsive Design: Built with Jetpack Compose, the app's UI adapts seamlessly to various screen sizes and orientations.

# COMPONENTS

The ToDo App consists of several key components that contribute to its functionality:

1) SplashActivity: The entry point of the app that displays a splash screen while initializing main components.

2) MainActivity: The central hub of the app, where users manage their tasks. It showcases tasks in a RecyclerView and enables users to add, edit, and delete tasks using intuitive gestures.

3) AddNewTask: A BottomSheetDialogFragment that provides an intuitive form for creating new tasks. Users can enter task details and save them seamlessly.

4) RecyclerViewTouchHelper: This class leverages ItemTouchHelper.SimpleCallback to enable swipe actions on tasks within the RecyclerView. Users can swipe tasks left to edit and right to delete.

5) OnDialogCloseListener: An interface that facilitates communication between components, ensuring prompt updates when dialogs are closed.

# ARCHITECTURE

The ToDo App follows a clean and modular architecture, separating concerns to improve maintainability and scalability. The architecture incorporates Jetpack Compose for UI rendering, allowing for a reactive and declarative approach to building user interfaces. Data handling is managed by the underlying Android architecture components, promoting best practices in Android development.

# DEPENDENCIES

The app leverages a selection of powerful libraries to enhance its functionality:

1) Jetpack Compose: Empowers the creation of dynamic and engaging user interfaces using a declarative syntax.

2) Material Components: Provides a consistent design language and components for a polished user experience.

3) RecyclerViewSwipeDecorator: Enhances task interaction by incorporating visual cues and animations during swipe gestures.

# USAGE

To utilize the ToDo App effectively, follow these steps:

1) Launch the app to access the splash screen, which seamlessly transitions into the main task management interface.

2) The main screen showcases your tasks. Swipe tasks left to edit details, or swipe right to delete them. Alternatively, tap a task to enter edit mode.

3) To add a new task, tap the "+" button at the bottom of the screen. This triggers a dialog where you can input task details. After providing the necessary information, tap "Save" to create the task.

# BUILDING AND RUNNING

To build and run the ToDo App:

1) Clone this repository to your local machine.

2) Open the project using Android Studio.

3) Build and run the app on an Android emulator or a physical device.
