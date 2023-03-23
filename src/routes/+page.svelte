<script>
	import Question from '../components/question.svelte';
	import Score from '../components/score.svelte';
</script>

<Score score={14} />

<Question
	number={1}
	answer1="First answer"
	answer2="Second answer"
	answer3="Third answer"
	answer4="Fourth answer"
>
	This is the question
</Question>
