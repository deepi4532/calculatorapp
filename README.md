# calculatorapp
<!DOCTYPE html>
<<html lang="en">
	<head>
		<LinearLayout
		xmlns:android="http://schemas.android.com/apk/res/android"
			android:layout_width="match_parent"
			android:layout_height="match_parent"
			android:orientation="vertical"
			android:padding="16dp">
		 
			<EditText
				android:id="@+id/input1"
				android:layout_width="match_parent"
				android:layout_height="wrap_content"
				android:hint="Enter first number"
				android:inputType="numberDecimal" />
		 
			<EditText
				android:id="@+id/input2"
				android:layout_width="match_parent"
				android:layout_height="wrap_content"
				android:hint="Enter second number"
				android:inputType="numberDecimal" />
		 
			<TextView
				android:id="@+id/result"
				android:layout_width="match_parent"
				android:layout_height="wrap_content"
				android:text="Result"
				android:textSize="18sp"
				android:gravity="center" />
		 
			<Button
				android:id="@+id/addButton"
				android:layout_width="match_parent"
				android:layout_height="wrap_content"
				android:text="Add" />
		 
			<Button
				android:id="@+id/subtractButton"
				android:layout_width="match_parent"
				android:layout_height="wrap_content"
				android:text="Subtract" />
		 
			<Button
				android:id="@+id/multiplyButton"
				android:layout_width="match_parent"
				android:layout_height="wrap_content"
				android:text="Multiply" />
		 
			<Button
				android:id="@+id/divideButton"
				android:layout_width="match_parent"
				android:layout_height="wrap_content"
				android:text="Divide" />
		 
			<Button
				android:id="@+id/clearButton"
				android:layout_width="match_parent"
				android:layout_height="wrap_content"
				android:text="Clear" />
		 
			<Button
				android:id="@+id/historyButton"
				android:layout_width="match_parent"
				android:layout_height="wrap_content"
				android:text="History" />
	</LinearLayout>
			</p>
		</div>
	</body>
</html>
