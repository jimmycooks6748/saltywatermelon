<script>
	import Question from '../components/question.svelte';
	import Score from '../components/score.svelte';
	import Answer from '../components/answer.svelte';
</script>

<Score score={14} />

<Question
	number={1}
	answer1="First answer"
	answer2="Second answer"
	answer3="Third answer"
	answer4="Fourth answer"
	answer="a"
>
	This is the question!
</Question>

<Question
	number={1}
	answer1="First answer"
	answer2="Second answer"
	answer3="Third answer"
	answer4="Fourth answer"
	answer="b"
>
	This is the question!
</Question>

<Question
	number={1}
	answer1="First answer"
	answer2="Second answer"
	answer3="Third answer"
	answer4="Idk"
	answer="c"
>
	Why is the sky blue!
</Question>

<Question
	number={1}
	answer1="First answer"
	answer2="Second answer"
	answer3="Third answer"
	answer4="Fourth answer"
	answer="d"
>
	Why does wood float!
</Question>

