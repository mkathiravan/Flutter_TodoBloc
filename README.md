## Equatable: (class MyFormState extends Equatable)

For comparison of data, we required Equatable. it overrides == and hashCode internally, which saves a lot of boilerplate code. In Bloc, we have to extend Equatable to States and Events classes to use this functionality.


→ **Pure** means the property has not been touched.(const Email.pure([String value = '']) : super.pure(value);
)


**FocusNode**:
Use the FocusNode to identify a specific TextField in Flutter's “focus tree.” This allows you to give focus to the TextField in the next steps.
