… (Dmitry Gorshckov)
 
… (Address (97/42, Vosstanya, Kazan, Republic of Tatarstan, Russia))
… (13/05/1990)
Cellular phone: …(8(963)1252010r), Home phone: … (8(843)324567)
E-mail: parkerr89@yandex.ru

SUMMARY                    I want to learn something new! I think mobile development is                                           interesting. I would like to write a good application.
		
 
SKILLS  

CODE EXAMPLES,EXPERIENCE        public class MainActivity extends AppCompatActivity {

                       private Button mTrueButton;
                       private Button mFalseButton;


    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        mTrueButton = findViewById(R.id.true_button);
        mFalseButton = findViewById(R.id.false_button);
        mTrueButton.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                Toast.makeText(MainActivity.this,
                        R.string.correct_toast,Toast.LENGTH_SHORT).show();
            }
        });
        mFalseButton.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {

                 Toast t = Toast.makeText(MainActivity.this,
                        R.string.incorrect_toast,Toast.LENGTH_SHORT);
                 t.setGravity(Gravity.TOP,0,100);
                 t.show();
            }
        });
    }
}


      
EDUCATION	                     Course (Java Industrial Development Fundamentals)

ENGLISH                            A1(base)
